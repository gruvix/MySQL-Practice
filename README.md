# MySQL-Practice
A practice SQL project where i learned about Database and local server hosting
Made a local hosted website using Wordpress__


To start the site you first need to instal XAMPP PHP development environment__
[XAMPP from Apache friends](https://www.apachefriends.org/)__
Then Download Wordpress__
[Wordpress official download site](https://wordpress.org/download/)__
and extract it inside ...\XAMPP\htdocs__
then follow the instructions from wordpress [Wordpress install guide](https://wordpress.org/support/article/how-to-install-wordpress/)

In summary create a database in http://localhost/phpmyadmin/index.php?route=/server/databases named "wordpress", edit the file called "wp-config-sample" inside wordpress folder and rename it to "wp-config", and change lines 23 to 38 to look like this:

define( 'DB_NAME', 'wordpress' );

/** Database username */
define( 'DB_USER', 'root' );

/** Database password */
define( 'DB_PASSWORD', '' );

/** Database hostname */
define( 'DB_HOST', 'localhost:3306' ); // You should check in XAMPP control panel what port is MySQL listening to, if you don't find it see image below

/** Database charset to use in creating database tables. */
define( 'DB_CHARSET', 'utf8' );

/** The database collate type. Don't change this if in doubt. */
define( 'DB_COLLATE', '' );
