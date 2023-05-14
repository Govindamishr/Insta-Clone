# Insta-Clone

:house: **Insta-Clone**

### ***Framework***
---------
- spring boot

-------------

### ***Project management tool***
-------
- Maven


-----------------
### ***DataBase***
****************
- MySql
****************

### **use of dependency**
-----
- <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-data-jpa</artifactId>
      </dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-web</artifactId>
     </dependency>

- <dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-devtools</artifactId>
	<scope>runtime</scope>
	<optional>true</optional>
	</dependency>
- <dependency>
    <groupId>com.mysql</groupId>
    <artifactId>mysql-connector-j</artifactId>
    <version>8.0.33</version>
 </dependency>

- <dependency>
       <groupId>org.projectlombok</groupId>
       <artifactId>lombok</artifactId>
       <optional>true</optional>
	</dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-test</artifactId>
     <scope>test</scope>
     </dependency>
<!-- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation -->
- <dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-validation</artifactId>
	<version>3.0.6</version>
	</dependency>





--------

### **packages and class**

---------
- model 
  - User
  - Post
  - AuthenticationToken
- dto
    - SignUpInput
    - SignUpOutput
    - SignInInput
    - SingInOuput


- controller
   - UserController
   - PostController

- service
   - PostService
   - UserService
   - TokenService
- Repository
  - IPostRepository
  - IUserRepository
  - ITokenRepository
 
-------------


### **Run tests**

------

⭕ postman 

:globe_with_meridians: chrome browser

********

### **Data structure And programming language**

-----

 - core java
 
 --------

  :point_down: **Summary**
*****
This project involves creating the basic design of the backend of Instagram, including defining the User, Post, and AuthenticationToken models. The User model includes fields for user authentication, such as firstName, lastName, age, email, and phoneNumber. The Post model includes fields for postId, createdDate, updatedDate, and postData. Additionally, the AuthenticationToken model includes fields for tokenId, token, and tokenCreationDate.

The API is split into two controllers: the UserController and PostController. The UserController includes methods for authentication, such as sign in, sign up, and update user details. The PostController includes methods for saving and retrieving posts.

Overall, the goal of this project is to establish a foundation for the backend of Instagram that can be expanded and built upon in future development.
*****

### **Show your Support** 
****
:star: Thankyou 

****
