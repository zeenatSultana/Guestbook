# Guest Book Application


### Feature and Scope:
Guestbook application consists of two types of users. <br/>
<ol>
 <li>Guests</li>
  <li>Administrator</li>
</ol>

#### Guests
<ul>
 <li>User needs to login in order to write a new entry in the guestbook</li>
 <li>Guestbook entry can be either a single image or a text</li>
</ul>

#### Administrator
<ul>
 <li>View all the entries posted by all the users</li>
 <li>Approve the entries</li>
 <li>Edit the entries</li>
 <li>Remove the entries</li>
</ul>

### Prerequisites
Tools used:
* Tool - Spring Tool Suite/Eclipse
* MySQL Workbench
* Git
* Java 11
* Maven

### Technologies Used
* Java 11
* Spring boot
* JSP, HTML, CSS
* Bootstrap, JQuery, JS
* MySQL

### Steps to Clone The Repository Application Locally:

1) Download this project from Git.
```
git clone https://github.com/zeenatSultana/Guestbook.git
```
2) Import the Project Using Eclipse
```
File -> Import -> Maven -> Existing Maven project -> spring-boot-admin
```
 

### To Run the Spring MVC Application:
`step 1`: Download this repository & do maven import.<br>  
`step 2`: Create schema with name `guestbook` and execute data base scripts to create table structures from [database.sql]and import the default data from file [scripts.sql]<br><br>
`step 3`: Go to the main class file and run as Java application.
`step 4`: Once the application starts, By default application will be deployed in 8080 port, and you can access it by using http://localhost:8080/ <br>

### Build Application
  To build the application using maven, use the command `mvn clean install`, this will create production ready jar file under target folder to deploy to any server.
  

### To Login to Application
     Navigate to the URL http://localhost:8080/ and use the below credentails to login and manage the application <br>
      -- To login as ADMIN Role -- UN/PW -- `admin/P@ssword123`. <br>
      -- To login as USER Role  -- UN/PW -- `user/P@ssword123` or `user2/P@ssword123` <br>
