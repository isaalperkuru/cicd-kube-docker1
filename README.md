## NOTE
- The web project used was not developed by me; instead, I utilized it to enhance my DevOps skills.
- Practiced containerization using Helm, Kubernetes (with 1 master and 2 worker nodes), and Docker.
- Implemented a comprehensive CI/CD pipeline employing Jenkins (Jenkinsfile as a code), Maven, Docker Hub, Helm, and SonarQube.
- Employed AWS EC2 instances for hosting Jenkins, SonarQube (serving as a Jenkins slave), and the Kubernetes master (serving as a Jenkins slave and facilitating cluster creation on AWS).

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


