# Maven - How to create a Java web application project
Maven 3, Spring 5 MVC, JUnit 5, Logback and Jetty web server. A simple web project to display a current date.




## 1. How to run this project?

### 1.1 Test it with Jetty web server.
```
$ git clone https://github.com/anandbanik/mspring-web-app.git
$ cd spring-web-app 
$ mvn jetty:run
```
Access http://localhost:8080


### 1.2 Create a WAR file for deployment :
```
$ git clone https://github.com/anandbanik/mspring-web-app.git
$ cd spring-web-app 
$ mvn package or mvn war:war
```
A WAR is generated at 'target/finalName'
