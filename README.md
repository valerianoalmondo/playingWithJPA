# playintWithJPA

## Project Overview

- Creating diagram to understand the whole picture of the project in my mind: http://draw.io.

![](img/playingWIthJPADiagram.png)

- Choosing to create this project with Spring initializr to make it fast and simple as possible: https://start.spring.io.

Specifically:

WEB
- Spring Web (Build web, including ERSTful, applications using Spring MVC, Uses Apache Tomcat as the default embedded container).

SQL
- Spring Data JPA (Persist data in SQL with Java Persistence API using Spring Data and Hybernate).
- PostgreSQL Driver
  A JDBC and R2DBC driver that allows Java programs to connect to a PostgreSQL database using standard, database independent Java code.

## Setting project

### Creating simple API

- Connecting to database a setting the app properties

### Section overview

- Creating another diagram

![image](https://user-images.githubusercontent.com/70283310/151865488-ccd82517-089e-4a05-9e57-886f0153a9bf.png)


### Creating student class

- Creating student class with properties

### @Entity

- Tell that class that we created, to be a table and also to attributes to be a column in our table

### @Sequence

- Create a sequence with our specified id

### @Column

- Adding add column annotation. Specifying our columns names

### @IntelliJ Data Source

- Solivng errors (assigning datasource, creating empty constructor)

### @Table and Constraints

- Rename the unique student email key
