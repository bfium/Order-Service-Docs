# Service-Oriented (Microservice) Archictecture 
## Order Service RESTfull API 
Representational state transfer (REST) describes an architectural style for applica- tions that communicate over a network. 
Originally, the concept of REST included a list of constraints for the design of distributed and scalable web applications. 
Over time, detailed protocols and specifications have emerged that give us well-defined guidelines for designing REST APIs. 

DEFINITION: REST is an architectural style for building loosely coupled and highly scalable APIs. REST APIs are structured around resources, entities that can be manipulated through the API.

Using the Database-per-service principle, which state that each microservice
owns a specific set of the data, and no other service should have have access to such data
except through an API.

The Online Shopping System case study is a highly distributed World Wide Web– based system 
that provides services for purchasing items such as cafes or cafe related utilities. 
The solution uses a service-oriented architecture with `multiple services`; 
`coordinator objects` are used to facilitate the integration of the services. 
In addition, object brokers are used to provide service registration, brokering, and discovery. 
