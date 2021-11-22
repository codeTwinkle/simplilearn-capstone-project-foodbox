# Foodbox
This project aims to design and develop an E-commerce website that lets people shop food items of different cuisines at affordable prices and deliver the products to their addresses. It was developed using Angular and Spring boot It was created as the Capstone Project for the Full Stack Java Developer course.

## Product Backlog:
### Programming:
1.	Create database and tables.
2.	Add some rows and metadata to the tables
3.	Initialize a Spring Boot project for the Back-End side.
4.	Create REST APIs with spring Data JPA Repositories.
5.	Create desired DAO methods for the Back-End side
6.	Create a new Angular project for the Front-End side.
7.	Create login and register pages and components.
8.	Add cache to the login user
9.	Logout user and remove cache
10.	Show all products to the home page.
11.	Show all products as cards.
12.	Create a product details component.
13.	Search a product by a category.
14.	Search a product by a keyword.
15.	Add products pages
16.	Filter by page number
17.	Sort product by different options
18.	Add products to the cart.
19.	Update total price in the cart status.
20.	Show the payment gate and review the list
21.	Add and remove products from the review list
22.	Update the total price in the payment gate
23.	Create the admin view 
24.	Update/Remove a product for the admin
25.	Add a new product for the admin
26.	Update the CSS design
27.	Add bootstrap and font awesome to the components. 
28.	Debug and test the project.
### Deployment:
29.	Upload project to GitHub.
30.	Create a t3.medium instance for master.
31.	Create a t3.micro instance for slave.
32.	Connect the two instances to the system
33.	Create a Pipeline project on Jenkins.
34.	Create a Jenkins file.
35.	Generate a SSH key for GitHub.
36.	Build the pipeline project.
37.	Deploy the project.

## Technologies and tools Used
- Angular: used in the front-end side to build modern single-page applications
- Spring Boot: used in the back-end side to create the REST API and retrieve data from a database.
- AWS EC2 instance:  to use the instances as a VM and deploy the application
- AWS RDS: to upload the database online.
- Jenkins: to build the project from GitHub.
- GitHub: to upload the source code of the project.
- MobaXterm: to the instance from Windows OS.
- Selenium: for automation and testing.
- Apache: to use it as a web server.
- HTML/CSS: to create and format the content of the pages.
- Bootstrap: to use some CSS and JavaScript designs.
- Maven: to manage the project.
- Visual Studio Code: to write and run the Angular code.
- IntelliJ: to write and run the Spring Boot code.
- MySQL: to use it as database management system.
- phpMyAdmin: to administrate and manage the database manually.

## Flowcharts of The Application
![Blank Diagram](https://user-images.githubusercontent.com/64940728/133873445-3eee3d7a-7d70-4b1d-8a67-cf709a9604fb.png)


## Core concepts used in the project. 
- Object-Oriented: used to create and model objects for users and their credentials.
- REST API: used to communicate between the back-end and the front-end sides.
- Data Access Object: to abstract and encapsulate all access to the data source.
- Object–Relational Mapping: to map the objects to the database.
- Databases: used to store and retrieve data.
- Data Sources: used to define a set of properties required to identify and access the database.
- Collections: used some collections such Arraylist to store collection of data. 
- Deployment: to deploy the local project to the end-users.
- Virtual Machine: use virtual instances to help to build, deploy and manage websites.
- Exception Handling: used to catch problems that arises in the code especially in I/O blocks.
- Single Web Page: apply the concept of a website that only contains one HTML page.


## AWS Website Link
http://ec2-15-185-146-219.me-south-1.compute.amazonaws.com/

## How to run the program locally
-	clone project
```clone git : git clone https://github.com/MujtabaMohsin/Foodbox```

-	Import the “\Back-End\foodbox\database\foodbox.sql” file to your database administration tool.
-	Go to “\Back-End\foodbox\src\main\resources\application.properties” file, open it.
-	Edit some values of the database’ properties to be suit to your database administration tool.
-	Run the back-end project as a maven project:
```cd to your project “Back-end\foodbox”```
```mvn compile```
```mvn exec:java -Dexec.mainClass=com.simplilearn.foodbox```
-	Open another command line for the front-end part.
-	cd to your project “Front-end-end\foodbox”
-	install the following:
-	
```npm install --save-dev```

```npm install @angular/localize --save```

```npm install bootstrap --save```

```npm install font-awesome –save```

-	Run using ng serve –open
-	It would be displayed in http://localhost:4200/


## Screenshots

![screenshot_1133](https://user-images.githubusercontent.com/64940728/133873673-2cc4f2a3-00c9-4484-839b-969534a0f57c.jpg)

other screenshots can be found in the Documentation & Screenshots file

