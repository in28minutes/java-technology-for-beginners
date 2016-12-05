# java-technology-for-beginners
In my 15 years of designing and developing more than 100 java web applications, I have learnt that techies love coining new terminologies. They are great as we don't need to explain each time but imagine the state of a beginning programmer or a non techie - a Tester or Business Analyst or your Product Owner. They hardly understand them. This guide is to demystify these terms through videos! 

As I find time, I will create more videos. Request some patience :) 

If you think, I'm missing an important topic, shoot an email or create a pull request!

If you have a great video for one of these topics, which does not have a video attached, submit a pull request!

## Languages/Frameworks/Data Formats
- Java
 - Spring
 	- Spring Boot
 	- Spring MVC
 	- Spring Data
 	- Spring Data Flow
 	- Spring Data Rest
 	- Spring Cloud
 	- Spring Batch
 	- Spring Initializr
 	- Spring Security
 	- Spring HATEOAS
 	- Spring Integration
 - Unit Testing 
 	- JUnit
 	- Mockito
 	- EasyMock
 	- PowerMock
 	- Cobertura
 	- Emma
 - Database
 	- Hibernate
 	- iBatis
 - Rest Services
 	- Jersey Framework
 	- Play Framework
 	- Spring REST (actually Spring MVC)
 - Others 
 	- Quartz
 	- Guava
 	- Guice
 	- EhCache
 	- Drools
 	- Apache Commons
- JavaScript
 - NodeJS
 - JQuery
 - AngularJS
 - Ember.js
 - React.js
 - Redux
 - ECMAScript
- CSS
 - Bootstrap
- Formats
 - XML
 - XPath
 - JSON
 - SOAP
 - Swagger
 - Spring Rest Docs
- Others
 - jHipster
 
## Java
- JDK
- JVM
- JRE
- JAR
- WAR
- EAR
- Classloader
- Annotations
- Platform Independence

## Concepts
- OOPS
 - Interface
 - Inheritance
 - Abstract Class
 - Coupling
 - Cohesion
 - Encapsulation
 - Polymorphism
 - Abstraction
- Mocking and Mock objects
- Dependency Management
- Readable Code
- Dependency Injection
- Inversion of Control
- Synchronization
- Logging
- Caching
- Exception Handling
- Cross Cutting Concerns
- Aspect Oriented Programming (AOP)
- Spring
 - Autowiring
 - Component Scan
 - Application Context

## Practices
- Coding Standards
- Code Review
- Refactoring
- Pair Programming
- Unit Testing
- Automation Testing
- Load Testing
- User Acceptance Testing (UAT)
- Test Driven Development (TDD)
- Behavior Driven Development (BDD)
- Acceptance Test Driven Development (ATDD)
- Continuous Integration (CI)
- Continuous Delivery (CD)
- DevOps

## Terminologies
- Cloud
- Big Data
- Microservices
 - Cloud Native Applications
 - 12 factor app
 - Micro front-end
 - HATEOAS
- Functional Programming
- Reactive Programming
- In memory Database
- SPA (Single Page Application)
- Code Quality
- Technical Debt
- Code Coverage
- Legacy Code
- Tech Design
- Evolutionary Design
- Code First
- Contract First
- Web Service
- RESTful Web Service
- Static Code Analysis (Security)
- Vertical Slice
- Internationalization or Localization
- Transaction Management
- NFR (Non Functional Requirements)
 - Authentication 
 - Authorization
 - Performance
 - Scalability
 	- Load Balancing
 - Availability
 - Resilience
 - Maintainability
 - Portability
 - Security
 	- Cross Site Scripting (XSS)
 	- SQL Injection
- Containerization

## Java EE
- JSTL
- JPA
- JAX-RS
- JAX-WS
- JAXB
- JMS

## Design
- Design Patterns
- 4 Principles of Simple Design
- SOLID principles
- UML

## Tools
- IDE
 - Eclipse
 - NetBeans
 - Intellij
- Code Quality
 - SonarQube
 - CheckStyle
 - PMD
 - Findbugs
- Application/Web/Http Servers
 - Tomcat
 - WebSphere
 - Weblogic
 - Lightweight
  - Jetty
  - Undertow
- API Gateways
- Distributed Cache
 - Hazelcast
- Databases
 - In memory
 	- H2
 	- HSQL
 - Big Data
 	- Mongo DB
 - Redis
- Build
 - Ant
 - Maven
 - Gradle
 - Nexus
- Message Brokers
 - Kafka
- Performance
 - jProfiler
 - VisualVM
- Productivity
 - jRebel 
- Continuous Integration
 - Jenkins
- Automation Testing
 - Selenium
- Integration
 - Camel
 - Spring Integration
 - ESB
- BDD
 - Cucumber
- Version Control
 - Git
 - Stash 
 - SVN
- Containerization
 - Docker
 - Kubernetes
- DevOps
 - Chef
- CMS
- Load Testing
 - JMeter

## Processes
- Agile
 - Scrum
- Kanban
- Waterfall

## Details

###Spring
The Spring Framework is a Java platform that provides comprehensive infrastructure support for developing Java applications. Spring handles the infrastructure so you can focus on your application.
http://docs.spring.io/spring/docs/current/spring-framework-reference/html/overview.html

#### Video
COMING SOON..

####What
- Lets Programmers focus on Business Logic
- Key feature is Dependency Management
 - Enables Testability
- Inversion of Control
- Application Context

####Why
- Why is Unit Testing Important?
 - Loose Coupling
 - Testable Code
- Plumbing Code
 - JDBC
 - JMS
- Clean Architecture
 - Easy implementation of cross cutting concerns
- Architectural Flexibility
 - Integration with other frameworks
- Design Patterns

####How
- Add a Maven Dependency

####Best Practices
- Use Spring Initializr
- Consider Spring Boot
- Write Unit Tests
- Use BOM
- Use Maven or Gradle

####Challenges
- Difficult for Starting Programmer to understand 
- Once You understand, you cannot stop using it!

####What Else?
- Spring Modules https://github.com/in28minutes/SpringIn28Minutes/blob/master/Spring%20Tutorial%20For%20Beginners%20with%20Examples_v2.pdf
- Spring Projects http://spring.io/projects
- Spring Initializr https://start.spring.io

####Course
https://www.udemy.com/spring-tutorial-for-beginners/

###Spring Boot
Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run". We take an opinionated view of the Spring platform and third-party libraries so you can get started with minimum fuss. Most Spring Boot applications need very little Spring configuration.
http://projects.spring.io/spring-boot/

####Video
COMING SOON.. Fingers crossed

####What 

- Reduces effort in starting up a project
 - How long does it take to start a new project?
 - What do you do in Sprint 0?
 - Integrating Frameworks may be complex!
 - Configuration Management
 - Logging
 - Transaction Management
 - Error/ Exception Handling
 - Monitoring & Health Checks
 - Integrate Unit Testing and Mocking Frameworks
 - Migrating to different version is tough
  - Incompatible Jars - Jar Hell
  - Which version of other frameworks (Hibernate etc..) to upgrade to?

####Why
- Reduce start up time of a project
- Microservice Architecture!
 - No of small projects increase exponentially
- Starter Projects make integration with other frameworks easy
 - spring-boot-starter-web-services - Starter for using Spring Web Services
 - spring-boot-starter-web - Starter for building web, including RESTful, applications using Spring MVC. Uses Tomcat as the default embedded container
 - spring-boot-starter-test - Starter for testing Spring Boot applications with libraries including JUnit, Hamcrest and Mockito
 - spring-boot-starter-hateoas - Starter for building hypermedia-based RESTful web application with Spring MVC and Spring HATEOAS
 - spring-boot-starter-jersey - Starter for building RESTful web applications using JAX-RS and Jersey. An alternative to spring-boot-starter-web
 - spring-boot-starter-security - Starter for using Spring Security
 - spring-boot-starter-data-jpa - Starter for using Spring Data JPA with Hibernate
 - spring-boot-starter-data-rest - Starter for exposing Spring Data repositories over REST using Spring Data REST
- Developer Tools
 - Easy to debug and hot deploy!
 
####How
- Spring Initializr https://start.spring.io

####Challenges
- You need to understand Spring to solve problems
- Standardize a little before you use Spring Boot in all your microservices
- Make sure to put right security around Actuator

#####Deployment & Scalability
- Can be deployed to Cloud Services easily.

####Course

###Spring MVC

####Video
https://www.youtube.com/watch?v=BjNhGaZDr0Y

####What
- Great MVC & Rest Services Framework
- Loosely Coupled Design
- Support for multiple view technologies
- Integrates well with all popular frameworks

####Course
ADD_LATER

###Spring Data Rest
####Video

####What
- Expose Services from your Data without a lot of code
####Why
####How
####When
####Where
####Best Practices
####Challenges
####What Else?
####Tips
####Perspectives
#####Code
#####Test
#####Design
#####Architecture
#####Management
#####Deployment
#####Operations
#####Performance
#####Scalability
#####Maintainability
#####Availability
#####Security
####Course


###Topic
####Video
####What
####Why
####How
####When
####Where
####Best Practices
####Challenges
####Example
####What Else?
####Tips
####Perspectives
#####Code
#####Test
#####Design
#####Architecture
#####Management
#####Deployment
#####Operations
#####Performance
#####Scalability
#####Maintainability
#####Availability
#####Security
####Course

####What Else?
- Spring Modules https://github.com/in28minutes/SpringIn28Minutes/blob/master/Spring%20Tutorial%20For%20Beginners%20with%20Examples_v2.pdf
- Spring Projects http://spring.io/projects
- Spring Initializr https://start.spring.io

####Course
https://www.udemy.com/spring-tutorial-for-beginners/

###Spring Boot
####Video

####What http://projects.spring.io/spring-boot/
- How long does it take to start a new project?
- What do you do in Spring 0?
- Integrating Frameworks may be complex!
- All other stuff
 - Configuration Management
 - Logging
 - Transaction Management
 - Error/ Exception Handling
 - Monitoring & Health Checks
 - Integrate Unit Testing and Mocking Frameworks
- Migrating to different version is tough
 - Incompatible Jars - Jar Hell
 - Which version of other frameworks (Hibernate etc..) to upgrade to?

####Why
- Reduce start up time of a project
- Microservice Architecture!
 - No of small projects increase exponentially
- Starter Projects make integration with other frameworks easy
- Developer Tools
 
####How
- Spring Initializr https://start.spring.io

####Challenges
- You need to understand Spring to solve problems
- Standardize a little before you use Spring Boot in all your microservices
- Make sure to put right security around Actuator

#####Deployment & Scalability
- Can be deployed to Cloud Services easily.

####Course

###Spring MVC
####Video
https://www.youtube.com/watch?v=BjNhGaZDr0Y
####What
- Great MVC & Rest Services Framework
- Loosely Coupled Design
- Support for multiple view technologies
- Integrates well with all popular frameworks
####Course
ADD_LATER

###Spring Data Rest
####Video

####What
- Expose Services from your Data without a lot of code
####Why
####How
####When
####Where
####Best Practices
####Challenges
####What Else?
####Tips
####Perspectives
#####Code
#####Test
#####Design
#####Architecture
#####Management
#####Deployment
#####Operations
#####Performance
#####Scalability
#####Maintainability
#####Availability
#####Security
####Course


###Topic
####Video
####What
####Why
####How
####When
####Where
####Best Practices
####Challenges
####What Else?
####Tips
####Perspectives
#####Code
#####Test
#####Design
#####Architecture
#####Management
#####Deployment
#####Operations
#####Performance
#####Scalability
#####Maintainability
#####Availability
#####Security
####Course
