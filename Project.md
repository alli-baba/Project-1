# Project 1 Documentation


## update a list of packages in package manager


`sudo apt update`


![Apache Update](./Images/Apache%20update.png)



## run apache2 package installation


`sudo apt install apache2`


![install apache2](./Images/install%20apache2.png)




## To verify that apache2 is running as a Service in our OS


`sudo systemctl status apache2`


![systemctl status apache2](./Images/systemctl%20status%20apache2.png)



## Installing MYSQL


`sudo apt install mysql-server`



![installing mysql-server](./Images/installing%20mysql-server.png)



## Installing PHP

`sudo apt install php libapache2-mod-php php-mysql`


![installing PHP](./Images/Installing%20PHP.png)



##  Creating a virtual host for your website using apache


`sudo vi /etc/apache2/sites-available/projectlamp.conf`




![Creating a virtual host for your website using apache](./Images/Creating%20a%20virtual%20host%20for%20your%20website%20using%20apache.png)


## Enable php on the website


`sudo vim /etc/apache2/mods-enabled/dir.conf`





![Enable php on the website](./Images/Enable%20php%20on%20the%20website.png)




## Create a new file named index.php



`vim /var/www/projectlamp/index.php`



![Enable php on the website](./Images/Create%20a%20new%20file%20named%20index.php.png)


# PHP installation is working as expected.


![Enable php on the website](./Images/PHP%20installation%20is%20working%20as%20expected..png)
