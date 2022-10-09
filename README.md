# MySQL-Practice
A practice SQL project where i learned about Database and local server hosting<br />
Made a local hosted website using Wordpress  


To start the site you first need to instal XAMPP PHP development environment  
[XAMPP from Apache friends](https://www.apachefriends.org/)  
Then Download Wordpress  
[Wordpress official download site](https://wordpress.org/download/)  
and extract it inside ...\XAMPP\htdocs  
then follow the instructions from wordpress [Wordpress install guide](https://wordpress.org/support/article/how-to-install-wordpress/)  
In summary create a database in http://localhost/phpmyadmin/index.php?route=/server/databases named "wordpress", edit the file called "wp-config-sample" inside wordpress folder and rename it to "wp-config", and change lines 23 to 38 to look like this: 

define( 'DB_NAME', 'wordpress' );  

/** Database username */  
define( 'DB_USER', 'root' );  

/** Database password */  
define( 'DB_PASSWORD', '' );  

/** Database hostname */<br />
define( 'DB_HOST', 'localhost:3306' ); // You should check in XAMPP control panel what port is MySQL listening to, if you don't find it see image below<br />

/** Database charset to use in creating database tables. */<br />
define( 'DB_CHARSET', 'utf8' );<br />

/** The database collate type. Don't change this if in doubt. */<br />
define( 'DB_COLLATE', '' );<br />

![alt text](https://github.com/gruvix/MySQL-Practice/blob/main/MySQLPort.png)<br />
