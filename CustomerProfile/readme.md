## Customer UI API 

This API microservice template is implemented to handle customer operations like create, update and delete customer profiles.  

This is only configured to run REST JSON APIs. Not configured to run any Web Application.  

**What's Configured**  

This microservice has been configured with:  

  - Spring boot starter parent  

 - Basic Spring boot Actuator  

 - Swagger  

 - Basic HTTP Authentication 

 - Unit tests including Spring boot starter test, Mockito and Hamcrest  

 - Loggers - Info

## Structure

Code was structure in the following way under the package `com.application.customer.ui`:

| Package | Description |

|--|--|

| config | Contains config classes for SpringSecurity, Swagger

   | core| Contains core classes like ApiResponse, ErrorObjects, Exceptions for REST APIs

   | customer| Contains model classes, RestController and Service for Customer operations

 **How to run it locally**

mvn spring-boot:run -Dspring.profiles.active=dev