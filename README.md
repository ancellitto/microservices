# Microservices with Spring Boot using Fiegn,Ribbon and Eureka
experimenting with various microservices based technologies,
there is core forex-service which provides conevsrtion rate of various currencies, Its built using spring boot and is exposed to eureka server for service discovery
Currency Converstion Microservice  uses forex service by using a Fiegn http client to call the forex microservice
multiple instance can be up which is loadbalanced using ribbon and discovered using Eureka naming server
