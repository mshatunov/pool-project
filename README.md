# Pool project
> work in progress  

Set of rest API's and infrastructure components for swimming pool management

## REST API

### Customer api
https://github.com/mshatunov/pool-api-customer  
customers management  
- spring boot 2 microservice
- mongo persistence

### Instructor api
https://github.com/mshatunov/pool-api-instructor    
pool instructor management
- spring boot reactive microservice 
- reactive mongo db

### Schedule api
https://github.com/mshatunov/pool-api-schedule    
pool schedule management
- spring boot 2 microservice
- mongo persistence
- feign

## Testing
- junit 5
- mockito

## Infrastructure

### Kubernetes deployment of whole project
https://github.com/mshatunov/pool-infra-kubernetes-config

### Spring cloud config server
https://github.com/mshatunov/pool-infra-config-server

### Configs for config server
https://github.com/mshatunov/pool-infra-configs

### Eureka service discovery
https://github.com/mshatunov/pool-infra-eureka-server