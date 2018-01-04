# Spring Boot Routering and Filtering
A simple microservice application and then build a reverse proxy application that uses Netflix Zuul to forward requests to the service application. You’ll also see how to use Zuul to filter requests made through the proxy service.

### Requirements
    Java JDK 1.8
    Maven

### Usage
In a browser, visit one of the Student application’s endpoints via the Gateway application. If you’ve used the configuration shown in this guide, you can access the Student service directly at localhost:8090 and via the Gateway service at localhost:8080/student.

http://localhost:8090/available

Visit one of the Student service endpoints, as localhost:8080/student/available, and you should see your request’s method logged by the Gateway application before it’s handed on to the Student application

http://localhost:8080/student/available

Zuul Gateway: an edge service application that can proxy and filter requests for your microservices.

### Reference
[Routing and Filtering](https://spring.io/guides/gs/routing-and-filtering/)
[Router and Filter: Zuul](https://cloud.spring.io/spring-cloud-netflix/multi/multi__router_and_filter_zuul.html)
