  # Microservices com Java Spring Cloud, Spring Boot e Docker 🍃
  
   [![Continuos Integration with Github](https://github.com/eliezermoraesss/microservices-java-spring-cloud-docker_compose/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/eliezermoraesss/microservices-java-spring-cloud-docker_compose/actions/workflows/docker-publish.yml)
 
 ## Endpoints para teste: 🧪
 
Eureka (Naming Server) --> http://localhost:8761/<br>
Zipkin                 --> http://localhost:9411/zipkin/<br>
API Gateway Swagger    --> http://localhost:8765/swagger-ui.html<br>
API Gateway Cambio     --> http://localhost:8765/cambio-service/{amount}/{original_currency}/{to_currency}<br>
API Gateway Book       --> http://localhost:8765/book-service/{amount}/{to_currency}<br>
Cambio Microservice    --> http://localhost:8001/cambio-service/{amount}/{original_currency}/{to_currency}<br>
Book Microservice      --> http://localhost:8100/book-service/{amount}/{to_currency}<br>

## Tecnologias usadas:
 
Spring Cloud Configuration;<br>
Spring Boot Actuator;<br>
Feign;<br>
Service Discovery e Service Registry com Eureka;<br>
Load Balancing com Eureka, Feign e Spring Cloud LoadBalancer;<br>
API Gateway e RouteLocator com Spring Cloud Gateway;<br>
Circuit Breaker com Resilience4j;<br>
Configuração do Swagger OpenAPI nos microsserviços;<br>
Distributed Tracing com Docker, Zipkin, Eureka e Sleuth;<br>
Dockerização (Docker Compose), entrega contínua com Github Actions.<br>

## Tecnologias atualizadas:

Anteriormente      -->  Hoje <br>
Hystrix                   -->  Resliience4J<br>
Ribbon                   -->  Spring Cloud Load Balancer<br>
Zuul 1                    -->  Spring Cloud Gateway<br>
Archaius 1            -->  Spring Cloud Config<br>
