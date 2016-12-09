# java-technology-for-beginners
In my 15 years of designing and developing more than 100 java web applications, I have learnt that techies love coining new terminologies. They are great as we don't need to explain each time but imagine the state of a beginning programmer or a non techie - a Tester or Business Analyst or your Product Owner. They hardly understand them. This guide is to demystify these terms through videos! 

As I find time, I will create more videos. Request some patience :) 

If you think, I'm missing an important topic, shoot an email or create a pull request!

If you have a great video for one of these topics, which does not have a video attached, submit a pull request!

## Presentation Template
- https://app.mindmup.com/map/_free/ff0bce00baa611e6ae8525496545fc76

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
ADD_LATER

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
Spring Data REST is part of the umbrella Spring Data project and makes it easy to build hypermedia-driven REST web services on top of Spring Data repositories. http://projects.spring.io/spring-data-rest/
org.springframework.boot:spring-boot-starter-data-rest

####Video
COMING SOON

####What
- Expose Services from your Data without a lot of code
- Supports SQL based and No SQL based databases
- Pagination
- Filtering
- Sorting
- HATEOAS
- defaultPageSize

####Why
- Simple Projects want to quickly expose Rest Services

####How
- Simplest way is to use the Spring Boot Starter Project

####Challenges
- Not recommended for Complex Applications 

####Example Code
\pom.xml
```
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>com.in28minutes</groupId>
	<artifactId>spring-data-rest-example</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>1.4.2.RELEASE</version>
	</parent>

	<properties>
		<java.version>1.7</java.version>
	</properties>

	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-rest</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>

		<dependency>
			<groupId>com.h2database</groupId>
			<artifactId>h2</artifactId>
		</dependency>

	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

	<repositories>
		<repository>
			<id>spring-releases</id>
			<url>https://repo.spring.io/libs-release</url>
		</repository>
	</repositories>
	<pluginRepositories>
		<pluginRepository>
			<id>spring-releases</id>
			<url>https://repo.spring.io/libs-release</url>
		</pluginRepository>
	</pluginRepositories>
</project>
```
\src\main\java\com\in28minutes\Application.java
```
package com.in28minutes;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class Application {

	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}
}
```
\src\main\java\com\in28minutes\data\Todo.java
```
package com.in28minutes.data;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;

@Entity
public class Todo {

	@Id
	@GeneratedValue(strategy = GenerationType.AUTO)
	private long id;

	private String user;

	private String desc;

	private boolean isDone;

	public long getId() {
		return id;
	}

	public String getUser() {
		return user;
	}

	public void setUser(String user) {
		this.user = user;
	}

	public String getDesc() {
		return desc;
	}

	public void setDesc(String desc) {
		this.desc = desc;
	}

	public boolean isDone() {
		return isDone;
	}

	public void setDone(boolean isDone) {
		this.isDone = isDone;
	}

	@Override
	public String toString() {
		return String.format(
				"Todo [id=%s, user=%s, desc=%s, isDone=%s]",
				id, user, desc, isDone);
	}

}
```
\src\main\java\com\in28minutes\data\TodoRepository.java
```
package com.in28minutes.data;

import java.util.List;

import org.springframework.data.repository.PagingAndSortingRepository;
import org.springframework.data.repository.query.Param;
import org.springframework.data.rest.core.annotation.RepositoryRestResource;

@RepositoryRestResource(collectionResourceRel = "todos", path = "todos")
public interface TodoRepository
		extends PagingAndSortingRepository<Todo, Long> {

	List<Todo> findByUser(@Param("user") String user);

}
```


#### Example Execution
```
POST to http://localhost:8080/todos
Use Header => Content-Type:application/json
Request:

{
  "user": "Jill",
  "desc": "Learn Hibernate",
  "done": false
}

Response:

{
  "user": "Jill",
  "desc": "Learn Hibernate",
  "done": false,
  "_links": {
    "self": {
      "href": "http://localhost:8080/todos/1"
    },
    "todo": {
      "href": "http://localhost:8080/todos/1"
    }
  }
}
```
http://localhost:8080/todos
```
{
  "_embedded" : {
    "todos" : [ {
      "user" : "Jill",
      "desc" : "Learn Hibernate",
      "done" : false,
      "_links" : {
        "self" : {
          "href" : "http://localhost:8080/todos/1"
        },
        "todo" : {
          "href" : "http://localhost:8080/todos/1"
        }
      }
    } ]
  },
  "_links" : {
    "self" : {
      "href" : "http://localhost:8080/todos"
    },
    "profile" : {
      "href" : "http://localhost:8080/profile/todos"
    },
    "search" : {
      "href" : "http://localhost:8080/todos/search"
    }
  },
  "page" : {
    "size" : 20,
    "totalElements" : 1,
    "totalPages" : 1,
    "number" : 0
  }
}
```
http://localhost:8080/todos/1
```
{
  "user" : "Jill",
  "desc" : "Learn Hibernate",
  "done" : false,
  "_links" : {
    "self" : {
      "href" : "http://localhost:8080/todos/1"
    },
    "todo" : {
      "href" : "http://localhost:8080/todos/1"
    }
  }
}
```
- http://localhost:8080/todos?user=Jill
- http://localhost:8080/todos/search/findByUser?user=Jill

###Spring Cloud
Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems http://projects.spring.io/spring-cloud/ 

####Video
COMING SOON

####What
- What is Cloud?
- Why Cloud?
- Features of Spring Cloud
 - Configuration management 
 - Service discovery
 - Circuit breakers
 - API Gateway
 - Routing

Projects
- Spring Cloud Config 
- Spring Cloud Netflix : Integrates with Netflix OSS components (Eureka, Hystrix, Zuul...)
- Spring Cloud Security : OAuth2 rest client support.
- Spring Cloud Data Flow : Orchestration service for microservice. Create microservice based data pipelines using
 - DSL
 - Drag-and-drop GUI
 - REST-APIs 

####Why
- Cloud Native Applications vs Micro Services
 - Dynamic deployment to cloud needs a lot of automation
 
####How
- Spring Boot Starter Project

####Challenges
- Its still a young evolving set of projects. Experience of Netflix is surely a good thing.

###Spring Batch
A lightweight, comprehensive batch framework designed to enable the development of robust batch applications vital for the daily operations of enterprise systems. 
http://projects.spring.io/spring-batch/

####Video
Coming Soon

####Why
- Restartability : Easy to restart a batch program from where it failed
- Different Readers and Writers : Provides great support to read from JMS, JDBC, Hibernate, iBatis etc. It can write to JMS, JDBC, Hibernate and more.
- Chunk Processing : If we have 1 Million records to process, these can be processed in configurable chunks (1000 at a time or 10000 at a time).
- Easy to implement proper transaction management even when using chunk processing.
- Easy to implement parallel processing. With simple configuration, different steps can be run in parallel.

####What
A Job in Spring Batch is a sequence of Steps. Each Step can be configured with
- next : next step to execute
- tasklet : task or chunk to execute. A chunk can be configured with a Item Reader, Item Processor and Item Writer.
- decision : Decide which steps need to executed.

A Job Launcher can be used to execute a Spring Batch Job. A job can be launched/scheduled in a web container as well.
- Each execution of a job is called a Job Instance. Each Job Instance is provided with an execution id which can be used to restart the job (if needed).
- Job can be configured with parameters which can be passed to it from the Job Launcher.

####How
```
<job id="job1">
    <split id="split1" task-executor="taskExecutor" next="step4">
        <flow>
            <step id="step1" parent="s1" next="step2"/>
            <step id="step2" parent="s2"/>
        </flow>
        <flow>
            <step id="step3" parent="s3"/>
        </flow>
    </split>
    <step id="step4" parent="s4"/>
</job>
```

####When
For Batch Programs

####Best Practices
- Be careful about Exception Handling and Transaction Management
- Be as near to data as possible
- Allocate enough memory
- Stress test from the start of the project. Identify production data volumes and evolve the application to meet those needs.

####What Else?
Spring Batch 3.0 supports JSR-352 -java specification for batch processing

###Spring Initializr
Quick Start for Spring Projects. http://start.spring.io/

####Video
Coming Soon....

####What
- Choose Maven or Gradle
- Choose Version of Spring Boot
- Add all the stuff you want!
- Download the project
- Run... Thats it!!!

####Why
- Awesome and Simple way to create Spring Boot Projects
- Supports more than 50 different frameworks

####How
- Lets do a quick demo!

####When
- Start of a project or when you want to do a quick prototype

###Spring Security
Authentication and Authorization framework. (What is Authentication?) http://projects.spring.io/spring-security/ 

####Video
Coming Soon..

####What
- Great support for authentication and authorization
- Provides out of the box support to prevent session fixation, clickjacking and XSS 

####Why
- Integrates well with Spring and Spring Boot Projects
- Proven Framework. You do not want to play with Authentication and Authorization.
- Great Integration with wide range of technologies
 - HTTP BASIC authentication headers
 - HTTP X.509 client certificate exchange
 - LDAP
 - Form based
 - JAAS

####How
- org.springframework.security:spring-security-web
- Or use the spring security starter project!

####Demo
Lets do a quick demo...

###Spring HATEOAS
Spring support for HATEOAS (Hypermedia as Representation of Application State) http://projects.spring.io/spring-hateoas/

####Video

####What
- Create services that include HATEOAS links in the response..
- Create clients for services using HATEOAS

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



Copy Again~~~~~~~~~~~~~~~~~~~~~~
###Topic
####Video
Coming Soon
####What
####Why
####How
####When
####Where
####Best Practices
####Challenges
####Example
####What Else?
####How to Learn?
####Related Topics
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

