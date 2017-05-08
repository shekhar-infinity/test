# Setup - LAMP

$ = Non Root User

&#35; = Root User

#### Setup LAMP on machine Linux 15.10.
1. Update System/Linux 15.10 machine 
```
$ sudo apt update
$ sudo apt upgrade
```

2. Install Apache2
```
# sudo apt install apache2 
# sudo service apache2 status
```

3. Install MySQL 
```
# sudo apt install mysql-server php5-mysql	 	
# sudo service mysql status
```
4. Install PHP
```
# sudo apt install php5 libapache2-mod-php5 php5-mcrypt

# sudo nano /var/www/html/info.php
# sudo service apache2 restart
```
----------------------------------------------------------------
