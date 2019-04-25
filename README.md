## Week 5

###  30th April/ 1st May 2019
At this point we have developed an Azure hosted Java Spring web application connected to an Azure SQL database.

The application **reads** products from the database and supports **creation** of new products which are inserted into the database.

The next class will add update and delete to complete the **CRUD** functionality (**C**reate, **R**ead, **U**pdate, and **D**elete). We will also add a product search function which will find products which include search words in their names or descriptions (using a like query). Try the completed app here: https://java-app2019.azurewebsites.net/products/


### 5.0 Preperation Exercise 

#### Create a Spring Boot web app and deploy to Azure
The web application should display a list of employees from an Azure SQL database. Employees should be organised by teir work department.

##### Steps
1. Create a new Azure Web app (configure for Java 1.8 + Tomcat)
..- If you have an existing web app then create a new App Service Plan when creating this app
2. Create a new Azure SQL database and add the required tables with sample data.
3. Build the webapp.
..- Include four pages with a shared navigation.
..- Layout and format using BootStrap 4.
4. Include a page for employees
..- List the employees in a table
..- Include a list of department links - when clicked show employees for that department.
5. Deploy the web app to Azure via FTP.

### 5.1 Updating Products
https://github.com/COM673/2019-Week5-CRUD/blob/master/5.1.SpringBootWebAppJDBC-UpdateProduct.pdf

### 5.2 Deleting Products
https://github.com/COM673/2019-Week5-CRUD/blob/master/5.2.SpringBootWebAppJDBC-DeleteProduct.pdf