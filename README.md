# How-to-connect-my-PHP-website-with-my-SQL
Create a database called  registration. In the registration database, add a table called users. The users table will take the following four attributes :
          id        - int
          username  -  varchar(100)
          email  -  varchar(100)
          password  -  varchar(100)
You can create this using a MySQL client like PHPMyAdmin Or you can create it on the MySQL prompt using the following SQL script:
 
CREATE TABLE `users` (
`id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
`username` varchar(100) NOT NULL,
`email` varchar(100) NOT NULL,
`password` varchar(100) NOT NULL
)
ENGINE=InnoDB DEFAULT CHARSET=latin1;
 
