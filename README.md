Building real time RestAPIS for Blogging Application using  SpringBoot,,SpringSecurity,JWT,Spring Data JPA(Hibernate) and MYSQL      
->Creating REST endpoints      
->Complex Db structure JPA Entities      
->Role based Authentication      
->Handling Exceptions            
->Using DTO for Data Transfer      
->Swagger      



How to add profilies for different environments
How to deploy springBoot in production


# Prerequisite
Core Java,Basic of SpringFramework (Spring Core DI,JPA,MVC),
SpringBoot,MySQL



# Client-Server Architecture
      request                        Server
Client -------------->               REST APIS       <---->     Database
      <--------------
         response



# REST
it's a software style created by Roy Fielding in 2000 to guide the design of architecture for the web.

REST
R-Representational ----Format json,xml
S-State          ----- Data
T-Transfer   ---Trasfer data between parties




# REST Guidelines
Client Server Architecture
Stateless
Cachelable
Layered System
Unform interface
Code on Demand (Optional)







# REST Concept
Resource
Sub resource
URI
Http Methods
Http Respone Code


Resource - Any thing that we want to expose to outside world, through our application.

URI(Uniform Resource Identifier) : Uri is used to identify resource.

Http Request Method- Http defines a set of request methods to indicate the desired action to be performed for a given resource

HTTP Response Codes--HTTP Response status codes indicate whether a specific HTTP request has been successfuly completed

200-OK
201-Created
401-Unauthorized
404-Not Found
500-Internal Server Error
















# what we are going to build Client Requirment
Clients wants blogging application where he/she can write blogs and articles.
user can comment on the blogs/article.





 we have to build simple blogging application:
 user should create, update, delete and lists posts.
 user should add update delete comment on posts.
 categories the post according to categories
 New user should able to Register on our application.
 User should able to login to our application.
 Post include one picture too.



 # Technical Term

Proper login and Register API.
Post API includes Pagination and Sorting.
Proper user input validation handling.
Proper exception handling.
Role based authentication-role security with apis
JWT based authentication.
Document all rest apis so that consumer can easy understand.
Deploy the backend application any cloud platform /AWS.



# Technologies
Java 8+
Maven
SpringBoot
Apache Tomcat
Spring Core, Spring Security(JWT), Spring Dta JPA(Hibernate)


MYSQL Database
Postman Rest Client
Swagger API Document
AWS EC2-Deploy


























         
