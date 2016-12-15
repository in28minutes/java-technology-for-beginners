# Java Technology for Beginners
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


###Cloud

####Video
Coming Soon

####What
- Dynamic provisioning of resources (computing, network, servers, applications) on need.

####Why
- Imagine a startup. Do you know how fast you will grow?
- Imagine a shopping company. Do you really need all the infrastructure you bought planning for the peak period (Black Friday, Holiday Season) during the lean periods of the year?
- Imagine applications for businesses have a year end peak period. What would the infrastructure be doing rest of the year?

####Types
- Private
- Public

####Advantages
- Agility 
- Cost reductions
- Scalability and elasticity 
- Reliability

####How
- Make sure your applications are Cloud Native
- Choose a platform
 - Microsoft Azure
 - AWS
 - Google's Cloud Platform 

####Best Practices
- 12 factor apps

####Challenges
- Security
- Application Compatibility 

####What Else?
- IaaS (Infrastructure as a Service)
- PAAS (Platform as a Service)
- SAAS (Software as a Service)

###Big Data

####Video
Coming Soon

####What
- Large volumes of data
 - Few dozen terabytes to many petabytes of data
- Data Sources
 - Social Networking - Facebook, Twitter
 - Cameras
 - Software Logs

####Why
- Faster, more intelligent decisions
- Business Trends

####How
- Different Parts
 - Capture
 - Storage & Transfer
 - Search
 - Analysis
 - Visualization

####Example
The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.
Modules
- Hadoop Common: The common utilities that support the other Hadoop modules.
- Hadoop Distributed File System (HDFS™): A distributed file system that provides high-throughput access to application data.
- Hadoop YARN: A framework for job scheduling and cluster resource management.
- Hadoop MapReduce: A YARN-based system for parallel processing of large data sets

###Microservices

####Video
Coming Soon

####What
- Keep it Small - Small methods, Small classes, Small Components, Small Services, Small Deployable Units. 
- Microservices are another step in the direction of “Keep it Small”. Fundamental change is to keep the deployable unit small.

####Why
- Many organizations found that embracing fine-grained, microservice architectures enable delivering software faster and adapt to new technologies. 
- Evolved from on the ground experiences at Netflix, eBay, Amazon, Groupon

####Characteristics
- Small, Lightweight
- Loosely coupled service-oriented architectures with bounded contexts
- Bounded Scope, Limited Scope, Solve one problem well
- Interoperable with message based communication
- Independently deployable and testable services
- Building systems that are replaceable over being maintainable
- Smart endpoints and dump pipes
 
####When
- When you are having problems taking your releases live!

####Advantages
- Faster Time To Market
- Experimentation and Speed of innovation
- Team Autonomy
- Independent Teams
- Scaling
- High Tuning Ability

####Challenges
- Identifying the right bounded contexts
- Challenges due to change in thinking towards event driven architectures
- Increased need for Automation
- More complex Monitoring & Application health management
- Fault Isolation
 - Correlation Ids
- Eventual Consistency through Standardization
 - Need to decide what you want to standardize and what you do not want to standardize.

####Microservices vs SOA
SOA started with similar aims. Let’s highlight a couple of significant differences.
- However, as time passed, SOA is characterized by large product based implementations arounds ESBs. These ESBs became the magnet for all business logic and over a period of time became the bottleneck. 
- Microservices approach place additional focus on microservices being autonomous and independently deployable.

####What Else?
- Spring Boot
- Spring Cloud

###Cloud Native Applications

####Video
Coming Soon

####What
Applications which are easily deployable on cloud.

####Challenges
- Visibility
- Fault Isolation
- Fault Tolerance
- Automated Recovery

####Other useful stuff 
- DevOps
- Continuous Delivery
- Microservices - Bounded Context & Choreography
- Containerization

####Best Practices
- 12 factors app
 - Codebase - One codebase tracked in revision control, many deploys
 - Dependencies - Explicitly declare and isolate dependencies
 - Config - Store config in the environment
 - Backing services - Treat backing services as attached resources
 - Build, release, run - Strictly separate build and run stages
 - Processes - Execute the app as one or more stateless processes
 - Port binding - Export services via port binding
 - Concurrency - Scale out via the process model
 - Disposability - Maximize robustness with fast startup and graceful shutdown
 - Dev/prod parity - Keep development, staging, and production as similar as possible
 - Logs - Treat logs as event streams
 - Admin processes - Run admin/management tasks as one-off processes

###12 Factor App
A methodology for building modern, scalable, maintainable software-as-a-service apps. Originated from developers at Heroku.

####Video
Coming Soon

####What
- Best practices for Cloud native applications.

####How
- 12 factors app
 - Codebase - One codebase tracked in revision control, many deploys
 - Dependencies - Explicitly declare and isolate dependencies
 - Config - Store config in the environment
 - Backing services - Treat backing services as attached resources
 - Build, release, run - Strictly separate build and run stages
 - Processes - Execute the app as one or more stateless processes
 - Port binding - Export services via port binding
 - Concurrency - Scale out via the process model
 - Disposability - Maximize robustness with fast startup and graceful shutdown
 - Dev/prod parity - Keep development, staging, and production as similar as possible
 - Logs - Treat logs as event streams
 - Admin processes - Run admin/management tasks as one-off processes

####Related Topics
- Cloud Native Applications

###Micro Frontend
Microservices With Front-End

####Video
Coming Soon

####Why
- Backend teams can't deliver business value without the frontend being updated
- Needs communication between frontend and backend teams
 
####What
A new approach to developing microservices, with both front-end and back-end included.

####Advantages
- Easy to take live - since only one microservice needs to be deployed
- One team works end to end!

####Challenges
- How to make sure that the individual frontends are consistent. Common Framework is an option. However the risk is the coupling a common framework might create
- Different UIs for different devices - Computer, Mobile, iPad etc.. 

###HATEOAS

####Video
Coming Soon

####What
- Hypermedia as the Engine of Application State. 
- One of the important constraints of REST application architecture. 
- Any REST service should include contextual hypermedia links with the response.

####Example
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

XML Example
```
<?xml version="1.0"?>
<account>
   <account_number>12345</account_number>
   <balance currency="usd">100.00</balance>
   <link rel="deposit" href="https://somebank.org/account/12345/deposit" />
   <link rel="withdraw" href="https://somebank.org/account/12345/withdraw" /> 
   <link rel="transfer" href="https://somebank.org/account/12345/transfer" />
   <link rel="close" href="https://somebank.org/account/12345/close" />
 </account>
```
####Why
- Less Coupling with URI Structures

####Related Topics
- HAL (Hypertext Application Language) is a simple format that gives a consistent and easy way to hyperlink between resources in your API.
- Resources have:
 - Links
 - Embedded Resources - other resources contained within them
 - State - the actual resource data
- Links have:
 - A target (a URI)
 - A relation (a name)

Example
``` 
{
    "links": {
        "self": { "href": "http://api.com/items" },
        "item": [
            { "href": "http://api.com/items/1" },
            { "href": "http://api.com/items/2" }
        ]
    "data": [
            {"itemName":"a"}, 
            {"itemName":"b"} 
     ] 
}
```
###Functional Programming
Should be driven with an Example!

###Reactive Programming
Should be driven with an Example!

###In memory Database
- IMDB or MMDB
- Main memory used as primary storage

####Why?
- In unit testing scenarios, you do not want to depend on external resources like a database. In memory databases help us to launch a database in memory, populate the data, run the tests and verify the results.
- Quick Prototyping and Learning

####What?
- Typically support a subset of the SQL (Structured Query Language) standard.
- Browser based console

####Examples
- H2 http://www.h2database.com/html/main.html
- HSQL

####How to use?
- Include a jar
- Point your datasource to the url
- Database is automatically created

####Demo
- Quick demo - Spring JDBC Example?

###SPA (Single Page Application)
- Load one page and dynamically update the page on user actions.
- Provides user experience similar to a desktop application.
- Typically use AJAX and HTML5
- Complete page is never reloaded!

####Demo
- http://demos.telerik.com/kendo-ui/websushi
- Gmail, Twitter and Facebook!

####How
Typical architectures involve 
- Building REST Services in the background! Java(most popular Spring Boot) or NodeJs
- Front-ends developed with frameworks like AngularJS, Ember.js, Meteor.js, ExtJS and React 

####Advantages
- Improved User Experience
- Reduced load on servers because only parts of page are reloaded
- Leads to more microservice based architectures!

####Challenges
- Needs completely different mindset!

####How to Learn?
- Start developing a quick app with AngularJS with a stubbed/mocked backend!

###Code Quality
Why duplicate? Reuse existing video?

###Technical Debt
- Cost of not using the best possible design and standards.
- Or how much cost is involved in getting to a good design meeting all standards
- Martin Fowler "extra effort that we have to do in future development because of the quick and dirty design choice"
- Impossible to measure accurately

####How is it measured?
- First thing: It cannot be measured perfectly! How do you find the technical debt because of wrong choice of technology, lack of common components, bad variable or method names.
- SonarQube - http://docs.sonarqube.org/display/SONARQUBE52/Technical+Debt
 - Measures technical debt against different Non Functional Requirements! Gives a SQALE rating!

####Consequences
As the application becomes bigger, the productivity of the team goes down. You would notice that the velocity of the team comes down.
 
####How to reduce Technical Debt?
- Simple Architecture (4 Principles of Simple Design)
- Continuous Refactoring
- Good Unit Tests 
- TDD
- Static Analysis
- Good Standards
- Peer Reviews
- Fingers crossed (Nobody can predict future architecture and when current architecture becomes obselete)
- Maintain a Technical Backlog
- Do a cleanup spring once in a while!

####Challenges?
- How do you improve a project which already has a large Technical Debt? 
 - Identify potential areas of improvement 
 - Identify changes in the next 6 months
 - Write test for areas which are gonna be changed in the next 6 months
 - Refactor
 - Build the test base over a period of time
 
####Best Practices
- Have Technical Debt as part of Definition of Done
- Measure Technical Debt from day one of the project!

###Code Coverage
How much percentage of your source code is covered by unit tests?

####Example
http://www.sonarqube.org/manage-code-coverage-by-unit-tests-with-sonar/

####Why is it important?
- Unit Testing is one of the most important modern development practices.
- Good Unit Tests are there for ever! They catch defects in future!
- Systems with good unit tests improve over a period of time! Developers are not worried about breaking functionality. So, they continuously refactor!

####Challenges
 - Not having proper asserts
 - Writing tests just for coverage!
 - Certains parts of the applications are not designed for unit testing
  - Old frameworks - Web and database especially

####How to measure?
- SONAR
- Eclipse - Cobertura and EclEmma plugins
- Inbuilt in Intellij

####Best Practices
- Have Code Coverage as part of Definition of Done
- Measure Code Coverage from day one of the project!

####Related Topics
Unit Testing
Dependency Injection
In memory databases

###Legacy Code
Make your choice
- Old Code!
- Code without Tests?
- Code with Lot of Technical Debt?
- Code with old out of date frameworks and languages?

####Challenges
- Unexpected impact - Changing one part of application impacts another part
- Large code bases
- Large teams
- Long Release Cycles

####Dealing with Legacy Code
- Refactor (atleast very important areas)
- Replace :)
- Have good code review process
- Introduce Static Analysis where possible
- Introduce Unit Testing where possible
- Measure Technical Debt
- Have Automated Regression Tests at least
 - Especially as writing good unit tests might be difficult
- Develop new functionality outside using new architecture and connect using services

####Related Topics
- Refactoring
- Code Quality

###Tech Design
- Lets not worry about it!

###Evolutionary Design
In water fall model, we followed an approach where we architected and designed the entire system before we started coding. Evolution Design is using a combination of good tests and high level architecture base to drive you to a good design. You apply basic design principles (4 Principles of Simple Design) and continuously refactor your code ensuring good design emerges. Uses an iterative approach.
At each pass - add, refactor and test 

####Advantages
- Avoids over design
- Avoids designing for some future feature which never materializes
- Continuous & Immediate feedback as we are not waiting for all design to complete before we deliver value to customer

####Challenges
- Need clear separation between Design and Architecture
- Need skilled and experienced developers/architects to guide and govern
- Needs Continuous Integration
- Needs high focus on tests. If tests are not good, design cannot evolve as developers are reluctant to make changes!

####Best Practices
- Use TDD
- Use Continuous Integration

####How to Learn?
- Good Question. Experience it to learn it. Pair with Good Programmers.

###Code First
When we develop any service, we have two approaches
- Code First
- Contract First

In Code First approach we write the code for the service first and generate the contract for the service from code!

####Examples 
Swaggerizing Spring Boot Services
Generating WSDL from Web Service Code

####Demo
Exposing Swagger contract from REST Services

####Advantages
- Does not need additional effort to create the contract!
- Contract and Code always in sync!

####Disadvantages
- Makes it difficult to develop in parallel!
- Teams do not know the target! As contract is not agreed ahead of time, teams might make more changes than necessary.
- In old frameworks, sometimes the generated contract was not compatiable across platforms!
- How do we support versioning?

####Move from WSDL to JSON REST Services
- Makes it more difficult to make a choice
- Tools are evolving. Today some of the disadvantages of Code First have alternatives. 

###Contract First
When we develop any service, we have two approaches
- Code First
- Contract First

In Contract First approach we agree on the contract for the service first. We write code based on the contract.

####Advantages
- Teams can develop in parallel!
- Teams know what to expect. Can use some stub framework to mock the service based on the contract.
- Cross Platform Compatible
- Enables reuse of Schemas

####Disadvantages
- Some initial additional effort
- Needs some effort to ensure that the updated contracts are shared as when needed

####Move from WSDL to JSON REST Services
- Makes it more difficult to make a choice
- Tools are evolving. Today some of the disadvantages of Code First have alternatives. 

###Web Service
- Everything on the web is a web service! 
- Fundamental to SOA and Microservice approaches.

####Example
- You send a request to Google.com. Google.com responds with HTML. Browser renders it.
![Example Web Service](http://3.bp.blogspot.com/-RSSyK3JhGhw/VVTOQyaX2jI/AAAAAAAAAL8/BZL6jYEZXL4/s640/WebService_BrowserGoogle.png)

####Some Terminologies
- Service Provider : Google.com is the service provider. Handles the request and sends a response back.
- Service Consumer : Browser is the service consumer. Creates Request. Invokes Service. Processes the Response.
- Data Exchange Format : In this example, Data Exchange is done over HTTP protocol. Request is HTTP request and Response is HTTP Response. Data exchange format can be something else as well. XML (in case of SOAP web services) and JSON (most RESTful services).
- Contract : Agreement to the definition of a service.

####Types of Webservices
- SOAP : Simple Object Access Protocol
- REST : RESTful Web services

####Advantages
- Re-use : Web services avoid the need to implement business logic repeatedly. If we expose a web service, other applications can re-use the functionality
- Modularity : For example, tax calculation can be implemented as a service and all the applications that need this feature can invoke the tax calculation web service. Leads to very modular application architecture.
- Language Neutral : Web services enable communication between systems using different programming languages and different architectures. For example, following systems can talk with each other : Java, .Net, Mainframes etc.
- Web Services are the fundamental blocks of implementing Service Oriented Architecture in an organization.

####Approaches to developing web services
- Contract First vs Code First
- SOAP vs REST
 - REST is winning the race. Lightweight. With JSON, more options for consumers.
- HTTP vs JMS vs AMQP vs...
 - As we move towards Microservices with event driven architectures, AMQP is getting more popular as a means of programming language neutral asynchronous communication approach. 
- Defining Contracts
 - WSDL for SOAP Services
 - Swagger/RestDocs for RESTful JSON Services

####Best Practices
- Keep your contracts programming language neutral
- Follow contract first
- JSON based RESTful services are emerging as a popular approach. They are lightweight and consumable from browser and mobile apps.

####Demo
- Let run a web service and call it using Postman?

### SOAP Web Services
- Refer web service section above for understanding what a web service is.
- In SOAP web services, data exchange (request and responses) happens using SOAP format. SOAP is based on XML.

####SOAP
- SOAP is a platform independent messaging protocol. Allows communication between disparate operation systems. For example, a system using Windows can talk to as sytem using UNIX using services built using SOAP protocol.
- SOAP format defines a SOAP-Envelope which envelopes the entire document. SOAP-Header (optional) contains any information needed to identify the request. Also, part of the Header is authentication, authorization information (signatures, encrypted information etc). SOAP-Body contains the real xml content of request or response.
- All the SOAP web services use this format for exchanging requests and responses. In case of error response, server responds back with SOAP-Fault.
![SOAP Web Services](http://4.bp.blogspot.com/-DyySh3d6XUs/VVTOTSlv3RI/AAAAAAAAAMQ/MGYhbgtYuo4/s640/WebService_SoapMessge.png)

####Steps in creating a SOAP Web Service
- Define a Contract
- Create Service Provider
- Create Service Consumer

#### How it works
Request/Response  Client Side	                        Server Side
Request           (1)Java Object => SOAP Request XML  ---o------->  (2)SOAP Request XML => C# Object
Response           (4)Java Object <= SOAP Response XML <----o-----  (3) SOAP Response XML <= C#Object

- Structure of Request and Response XML are defined in XML
- Frameworks like JAXB can convert object to xml and xml to object with WSDL as input

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

