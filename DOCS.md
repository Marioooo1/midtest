sudo apt-get update
sudo apt-get upgrade
sudo add-apt-repository ppa:ondrej/php
sudo apt-get update
sudo apt-get install nginx mariadb-server mariadb-client php7.2-fpm
sudo service nginx enable 
sudo service nginx start
sudo service nginx status
sudo service mariadb enable 
sudo service mariadb start
sudo service mariadb status
sudo service php7.2-fpm enable
sudo service php7.2-fpm start
sudo service php7.2-fpm status
sudo apt install curl
curl -4 icanhazip.com
sudo mysql_secure_instalitation
sudo mariadb
exit

cd /etc 
cd nginx/
cd sites-available/
ls
sudo cp default /etc/nginx
cd /etc/nginx
sudo mv default midtest
ls
sudo mv midtest /etc/nginx/sites-available
sudo nano midtest 
sudo  nginx -t
sudo ln -s /etc/nginx/sites-available/midtest /etc/nginx/sites-enable
sudo unlink /etc/nginx/sites-enable/default
sudo service nginx start
sudo service nginx reload
sudo service nginx status
sudo nano info.php
sudo rm info.php
sudo wget http://lionwiki.0o.cz/download/3.2.11/lionwiki-3.2.11.zip
ls

sudo unzip lionwiki-3.2.11.zip
ls
cd lionwiki-3.2.11/
ls
ls -al
sudo chmod +7 var
ls -al
terminal ls
sudo mv config.php index.php lang plugins templates var /var/www/html
ls
cd /var/www/html
ls
sudo rm lionwiki-3.2.11.zip
ls
