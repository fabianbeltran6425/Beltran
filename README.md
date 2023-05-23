# Beltran
SERVICIOS
sudo yum update
yum install vim
sudo yum install -y epel-release
sudo yum install python3-pip 
pip3 install Flask
sudo yum install wget 
wget http://repo.mysql.com/mysql-community-release-el7-5.noarch.rpm
sudo rpm -ivh mysql-community-release-el7-5.noarch.rpm
sudo yum install mysql-server 
sudo yum install mysql-devel 
sudo yum install gcc -y
sudo yum install python3-devel 
pip3 install flask-mysqldb
sudo systemctl start mysqld
mysql -u root -p
CREATE DATABASE myflaskapp;
use myflaskapp;
CREATE TABLE books (
    id int NOT NULL AUTO_INCREMENT PRIMARY KEY,
    title varchar(255),
    description varchar(255),
    author varchar(255)
);
INSERT INTO books VALUES(null, "La hojarasca", "Interesante", "Gabo"),
    (null, "El principito", "Brillante", "Antoine de Saint");

vim apirest_mysql.py
