# JIR-_CR-ck_BMB-ByHUNGBV
 Full Crack JIRA Tutorial:

==========>>>>>> I:Cr@ck All Version To 2089 !  <<<<<<<< ==========
> sudo systemctl stop jira

apt install openjdk-8-jre-headless 

git clone https://github.com/ithelpdeskBMBS/JIR-_CR-ck_BMB-ByHUNGBV.git

sudo mv /root/JIR-_CR-ck_BMB-ByHUNGBV/atlassian-agent.jar /opt/atlassian/jira/lib/

sudo sed -i "s/^export JAVA_OPTS/export JAVA_OPTS=\"-javaagent:\/opt\/atlassian\/jira\/lib\/atlassian-agent.jar \${JAVA_OPTS}\"/" /opt/atlassian/jira/bin/setenv.sh

sudo rm -rf /root/JIR-_CR-ck_BMB-ByHUNGBV

sudo chown -R jira /opt/atlassian/jira/lib/

sudo chown -R :jira /opt/atlassian/jira/lib/


==========>>>>>> II:Cr@ck Maximum Version 8.17.1 !  Unlimited time! User customization time! <<<<<<<< ==========

> sudo systemctl stop jira

apt install php7.4-cli

git clone https://github.com/ithelpdeskBMBS/JIR-_CR-ck_BMB-ByHUNGBV.git

remove files: atlassian-extras-x.x.jar and atlassian-universal-plugin-manager-plugin-x.x.x.jar For Jira Vesion From:

sudo find /opt/atlassian/jira/atlassian-jira/WEB-INF/lib/ -name 'atlassian-extras-*.jar' ! -name 'atlassian-extras-api-*.jar' -exec rm -f {} \;

sudo find /opt/atlassian/jira/atlassian-jira/WEB-INF/atlassian-bundled-plugins/ -name 'atlassian-universal-plugin-manager-plugin-*.jar' -exec rm -f {} \;

sudo mv /root/JIR-_CR-ck_BMB-ByHUNGBV/atlassian-extras-3.2.jar /opt/atlassian/jira/atlassian-jira/WEB-INF/lib/

*** sudo mv /root/JIR-_CR-ck_BMB-ByHUNGBV/atlassian-universal-plugin-manager-plugin-4.0.4.jar /opt/atlassian/jira/atlassian-jira/WEB-INF/atlassian-bundled-plugins/

sudo chown -R jira /opt/atlassian/jira/atlassian-jira/WEB-INF/

sudo chown -R :jira /opt/atlassian/jira/atlassian-jira/WEB-INF/

sudo find /opt/atlassian/jira/logs/ -type f -name "*.*" -delete

sudo rm -rf /var/atlassian/application-data/jira/.jira-home.lock

sudo rm -rf /opt/atlassian/jira/work/*.*

sudo rm -rf /root/JIR-_CR-ck_BMB-ByHUNGBV

sudo systemctl restart jira

sudo nano license_key.txt

Find the Server ID line: Add the current server ID

And edit the information you want!

save files

sudo php atlassian-keygen.php -e license_key.txt 

Copy key generate in console goto web paste key  - DONE

***Note: if the error is about 80%, remove the file atlassian-universal-plugin-manager-plugin-4.0.4.jar, copy the old file and restart jira
#hungbv
