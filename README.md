# jspringapp
# Following are the prerequisites for this java spring application
#--------------------------------------------~ Prerequisites ---------------------------------------------
~ JDK 1.8 or later
~ Maven 3 or later
~ MySQL 5.6 or later

#--------------------------------------------~ Technologies ---------------------------------------------
~ Spring MVC
~ Spring Security
~ Spring Data JPA
~ Maven
~ JSP
~ MySQL

#--------------------------------------------~ Database ---------------------------------------------
Database - Mysql DB 
MSQL DB Installation Steps for Linux ubuntu
~ $ sudo apt-get update
~ $ sudo apt-get install mysql-server

Then look for the file :
~ /src/main/resources/accountsdb
~ accountsdb.sql file is a mysql dump file. We have to import this dump to mysql db server
~ > mysql -u <user_name> -p accounts < accountsdb.sql
