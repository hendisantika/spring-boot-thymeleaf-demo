# Spring Boot Demo

### A Simple Spring Boot Demo

How to run this repo :

`mvn clean spring-boot:run`

Go to your browser :

`http://localhost:8080`

### Build Spring Boot Image

`mvn clean package`

### Build a Docker Image

Build the Docker image using following commands including the dot.

`docker build -f Dockerfile -t spring-boot-thymeleaf .`

Home Page

![Home Page](img/home.png "Home Page")

Add User Validation Page

![Add User Validation Page](img/validasi.png "Add User Validation Page")

List User Page

![List User Page](img/list.png "List User Page")