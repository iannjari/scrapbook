# API Design using Spring Beans Dependency injection

Dependency injection in Spring utilizes Beans (objects that are instantiated at boot time) and concept known as Autowiring. It is known as Autowirng beacause the Spring Framework 
does this process automatically.

In this article, we will use constructor based injection for demonstration. The example class will be a `student` class with the following properties:
- Id `id`,
- Name `name`,
- email `email`,
- Date of Birth `dob` and 
- Age `age`.

# Table of Contents

[Initializing a Spring Project](#initializing-spring-using-spring-initializr)

[Creating a Controller Class](#creating-a-student-controller-class)

[Creating a Service Class](#creating-a-student-service-class)

[Illustrating Dependency injection](#illustration-of-the-dependency-process)

# Initializing Spring using Spring Initializr
Go to https://start.spring.io/ and select the parameters in the following snippet or use [this link](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.3&packaging=jar&jvmVersion=17&groupId=com.example&artifactId=demo&name=demo&description=Demo%20project%20for%20Spring%20Boot%20Dep%20Injection&packageName=com.example.dependency&dependencies=web) for the populated fields.

`project:maven
spring boot: 2.6.3
package name: com.example.dependency
packaging: jar
java: 17
dependencies: Spring Web
`

Generate (CTRL + ENTER) the project files and unzip the folder then open the `/demo/` folder using an IDE of your choice.


Create a Java Package/Folder called `student` inside the `//` folder to contain the  demonstration Student class.

Inside it, create the Student class, `Student.java` and paste the code below:
```java
```

# Creating a Student Controller class

In this the `/student/` folder, create a class `StudentController` (a `StudentController.java` file). This will act as our API layer's controller.

Inside this class , by pasting the code in the following cell:

```java
```


# Creating a Student Service class

In this the `/student/` folder, create a class `StudentService` (a `StudentService.java` file). This will act as our Service layer's handler.

Inside this class , by pasting the code in the following cell:

```java
```
# Illustration of the Dependency process
In our example, 

# References




