# API Design using Spring Beans Dependency injection

Dependency injection in Spring utilizes Beans (objects that are instantiated at boot time) and concept known as Autowiring. It is known as Autowirng beacause the Spring Framework 
does this process automatically.

In this article, we will use constructor based injection for demonstration.

# Table of Contents

[Initializing a Spring Project]()

[Creating a Controller Class]()

[Creating a Service Class]()

[Demonstrating Dependency injection]()

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

