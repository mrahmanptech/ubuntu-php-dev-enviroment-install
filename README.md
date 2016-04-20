# ubuntu-php-dev-enviroment-install
All necessary Software in Ubuntu For Php Development. 

Skype Install :
---------------
sudo add-apt-repository "deb http://archive.canonical.com/ $(lsb_release -sc) partner"

sudo apt-get update 
sudo apt-get install skype


Apache Install :
----------------
apt-get install php5 php5-gd php5-mysql php5-curl php5-cli php5-cgi php5-dev
sudo apt-get install apache2 php5 libapache2-mod-php5

service apache2 restart

Mysql & Phpomyadmin Install :
-----------------------------
sudo apt-get install mysql-server
apt-get install phpmyadmin [before phpmyadmin install first install Mysql]

Extra Setings :
---------------
sudo a2enmod rewrite
sudo php5enmod mcrypt

Install Sublime :
-----------------
sudo add-apt-repository -y ppa:webupd8team/sublime-text-3
sudo apt-get update; 
sudo apt-get install -y sublime-text-installer


Install Git:
------------
sudo apt-get update
sudo apt-get install git


#Install Php Composer :
----------------------
sudo apt-get install curl php5-cli git
curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer



Misc. 
-----
Show Desktop :

Control + Super(Windows key) + D





