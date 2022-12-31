## NOTE
- This web project did not create by me.
- I used this project for practicing my DevOps skills.
- I used helm, kubernetes cluster (1 master and 2 worker node) and docker for containerazition.
- I used Jenkins (Jenkins file (Pipeline as a code)), maven, dockerhub, helm and Sonarqube for CICD pipeline.
- I used AWS EC2 instances for Jenkins, Sonarqube (Slave for jenkins) and Kubernetes master (Slave for jenkins and creating cluster with AWS).

## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


