# Eureka_zipkin_api_gateway

# building a microsevice application 
## Technologies 
1. ide intelij idea 
2. java 8 and above
3. spring boot
4. maven
## libaries and dependencies
1. hystix dashboard dependecies -controls the interaction between microservices to provide latency and fault tolerance. 
2. cloud configuration dependecies -  for storing and serving distributed configurations across multiple applications and environments.
    This configuration store is ideally versioned under Git version control and can be modified at application runtime.
3. helps you find out exactly where a request to the application has spent more time. Whether it's an internal call inside the code or an internal or external API call to another service, you can instrument the system to share a context.
4. slueth libraries -This library makes it possible to identify logs pertaining to a specific job, thread, or request. Sleuth integrates effortlessly with logging frameworks like Logback and SLF4J to add unique identifiers that help track and diagnose issues using logs.

## steps in implementing microservice 
1. create the services in your application
2. create eureka service registry which enables client-side load-balancing and decouples service providers from consumers without the need for DNS.The service registry needs to be updated each time a new service comes online and whenever a service is taken offline or becomes unavailable.
3. create Api gateway - offers a reverse proxy to redirect or route requests (layer 7 routing, usually HTTP requests) to the endpoints of the internal microservices. The gateway provides a single endpoint or URL for the client apps and then internally maps the requests to a group of internal microservices.
4. 

