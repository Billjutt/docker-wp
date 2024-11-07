# What is this ?
This Docker Compose script is for setting up, Wordpress, PHPMyAdmin and MariaDB based MYSql.

# How to Use it ?
Just CD into the directory and run the following command.

docker compose up

It will automatically, fetch the required docker images and set-up the wordpress, and run it.

# Prerequisit
1. Makesure docker is installed in your system.
2. .env File is created and must have the following variables declared.
    MYSQL_DATABASE=wp-database
    MYSQL_USER=wp-db-user
    MYSQL_PASSWORD=mysql-db-password
    MYSQL_ROOT_PASSWORD=mysql-root-password

# Why to use it ?
Best for Local Deployment and Plugins/themes testing.

Enjoy the Docker based Wordpress.
