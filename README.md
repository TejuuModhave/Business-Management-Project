﻿# Business-Management-Project
 
![Screenshot 2025-04-21 212251](https://github.com/user-attachments/assets/a1129987-b9ca-4302-b5b9-586eb9c77100)
# Business Management Web Application : <br>





## Project Desc : Business Management Web Application 
  => The Business Management Web Application is a comprehensive tool designed to help businesses manage various aspects of their operations. 
          It provides a user-friendly interface for tasks like managing customer data, inventory, orders, and more.



## Features  :

- **Customer Management**: Easily add, update, and delete customer information.
- **Inventory Management**: Keep track of your inventory items, including stock levels and pricing.
- **Order Management**: Manage customer orders such as order creation .
- **User Authentication**: Secure login and authentication for admin and staff members.
- **Role-Based Access Control**: Define roles and permissions for different user types.
- **Thymeleaf Templates**: Utilizes Thymeleaf for dynamic HTML templates.
- **Database Integration**: Integrated with MySQL for data storage.




## Technologies Used :

- Spring Boot: Backend framework for building Java-based web applications.
- Thymeleaf: Server-side Java template engine for dynamic HTML generation.
- MySQL: Relational database management system for data storage.
- IDE/Tool : IntelliJ IDEA




## Installation :

1. Clone the repository : $ git clonehttps://github.com/TejuuModhave/Business-Management-Project.git<br>

2. Import the project inside IntelliJ : <br>
     - Open IntelliJ > file > import > maven > existing project > browse > finish . <br>
     
3. Make sure you are in the Business_Management_Project directory. <br>

![Screenshot 2025-04-21 212505](https://github.com/user-attachments/assets/07601f7b-9afe-415a-853d-a8515800dc78)



4.Configure the database connection is application.properties (check the Database section for more information). <br>

5.Run the project (by running main method is BusinessProjectApplication.java) OR right clink on the project > Run As > Spring Boot App. <br>

6.Open http://localhost:8080/home in any browser. <br>

7.Now your tables will be created in the databse. <br>
   - You have to add one admin data manually to login as admin, So add one admin data. <br>
    



## Database :

MySQL can be used as the database for this project. 
The database connection can be configured in the application.properties file, with the appropriate values for the following properties: <br>

spring.datasource.name=[Your Database Name] <br>
spring.datasource.url=jdbc:mysql://localhost:3306/[Your Database Name] <br>
spring.datasource.password=[Your password] <br>
spring.datasource.username=[Your username] <br>
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver <br>
spring.jpa.hibernate.ddl-auto=update <br>
server.port=2330[Optional] <br>



## Preview :


#### Products 

![Screenshot 2025-04-21 212618](https://github.com/user-attachments/assets/61dd833a-2df4-475c-a410-68846534c3b0)


#### Location 


![Screenshot 2025-04-21 212802](https://github.com/user-attachments/assets/67c1b6b4-45d6-4b24-a9a2-39b9e61f5741)



#### Login Page


![Screenshot 2025-04-21 212853](https://github.com/user-attachments/assets/3c28e4a3-31c3-4eb8-b82e-7ca577186b67)




#### AdminPanel

![Screenshot 2025-04-21 213102](https://github.com/user-attachments/assets/6180076f-f0db-4424-a1a4-eec589acff86)



#### UserPanel 
![Screenshot 2025-04-21 212823](https://github.com/user-attachments/assets/b17a61ac-58b3-4b15-a6ab-895e4e3b8787)



### Exception page

![Screenshot 2025-04-21 213252](https://github.com/user-attachments/assets/086bdb35-2641-4116-9fd9-39cec0d50293)




