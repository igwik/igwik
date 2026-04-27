MariaDB

docker exec -it app_mariadb mariadb -u root -p

CREATE DATABASE dbname;

CREATE USER 'user'@'%' IDENTIFIED BY 'password';

GRANT ALL PRIVILEGES ON dbname.* TO 'user'@'%';

FLUSH PRIVILEGES;
