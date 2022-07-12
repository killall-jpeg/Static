sOCIAL BLOGPOST WEBSITE

A website for college students for posting blogs or images where one can make an account and view profile details, images and text posts.

SETUP

Install Xampp Control Panel and start the Mysql and apache servers.

The folder (Social_blogpost_website) with the codes must be saved in the folder htdocs in xampp.

Open localhost/phpmyadmin and create a database 'test_db' with two tables: posts and users1

The fields for the tables are:

create table posts(
id int(10),
postid bigint,
userid varchar(20),
post text,
image blob,
comments text,
likes tinyint(1),
date date,
has_image int(11)
)


create table users1(
email varchar(30),
fname varchar(10),
lname varchar(10),
user_name varchar(10),
password varchar(10),
bod date
)

The tables can directly be created in phpmyadmin.

HOW TO RUN:

Open Chrome (or any browser that supports html5)
Type localhost/Social_blogpost_website in the url bar
This will open the login page. Register for an account then continue to login with the same credentials. 
This will take you to the home page where you can post images or text and view the same.
 


