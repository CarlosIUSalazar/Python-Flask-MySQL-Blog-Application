# Python-Flask-MySQL-Blog-Application

##Necessary depencencies:

pip3 install flask   

pip3 install flask-bootstrap

pip3 install flask-ckeditor

pip3 install flask-wtf 

pip3 install flask-mysqldb  

pip3 install pyyaml

##Install MySQL on your terminal. Use the following to build the database and tables.

mysql -u root -p 

CREATE DATABASE flog_db

USE flog_db

CREATE TABLE user(user_id int auto_increment, first_name varchar(20), last_name varchar(20), username varchar(20) unique, email varchar(30) unique, password varchar(100), primary key(user_id));

CREATE TABLE blog(blog_id int auto_increment,title varchar(100), author varchar(40), body varchar(1000), primary key(blog_id));


