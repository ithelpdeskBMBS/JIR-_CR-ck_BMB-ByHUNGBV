# JIR-_CR-ck_BMB-ByHUNGBV
 Full Crack JIRA Tutorial:

apt install php7.4-cli

git clone https://github.com/ithelpdeskBMBS/JIR-_CR-ck_BMB-ByHUNGBV.git

cd ./JIR-_CR-ck_BMB-ByHUNGBV

remove files: atlassian-extras-x.x.jar and atlassian-universal-plugin-manager-plugin-x.x.x.jar For Jira Vesion From:

sudo find /opt/atlassian/jira/atlassian-jira/WEB-INF/lib/ -name 'atlassian-extras-*.jar' ! -name 'atlassian-extras-api-*.jar' -exec rm -f {} \;

sudo find /opt/atlassian/jira/atlassian-jira/WEB-INF/atlassian-bundled-plugins/ -name 'atlassian-universal-plugin-manager-plugin-*.jar' -exec rm -f {} \;

sudo mv atlassian-extras-3.2.jar /opt/atlassian/jira/atlassian-jira/WEB-INF/lib/

sudo mv atlassian-universal-plugin-manager-plugin-4.0.4.jar /opt/atlassian/jira/atlassian-jira/WEB-INF/atlassian-bundled-plugins/

sudo chown -R jira /opt/atlassian/jira/

sudo chown -R :jira /opt/atlassian/jira/

sudo systemctl restart jira

sudo nano license_key.txt
Tìm dòng Server ID: Thêm ID máy chủ hiện tại vào
Và sửa lại các thông tin mjnh mong muốn

save files
sudo php atlassian-keygen.php -e license_key.txt 

Copy key generate in console goto web paste key  - DONE
