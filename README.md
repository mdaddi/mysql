# mysql

mysql -u root -p -h IP -P 3306

show databases;

\s

SELECT SUBSTRING_INDEX(USER(), '@', -1) AS ip,  @@hostname as hostname, @@port as port, DATABASE() as current_database;
