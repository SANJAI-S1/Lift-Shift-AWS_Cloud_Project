# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

#Introduction 
This project is a hands-on, real-world implementation of a cloud migration strategy known as Lift and Shift (Rehost). The primary objective is to take an existing multi-tier web application that was running entirely on on-premise physical or virtual machines and migrate it — as-is — onto Amazon Web Services (AWS) cloud infrastructure, without modifying the application code.

The project covers the complete end-to-end migration journey: from provisioning cloud infrastructure and configuring security, all the way through to deploying the application, setting up DNS, configuring a load balancer, and finally building an elastic Auto Scaling Group — so the system can handle real-world traffic automatically.

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


