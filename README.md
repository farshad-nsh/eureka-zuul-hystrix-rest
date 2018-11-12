## Integrating Zuul and Eureka 
zuul is an edge server developed by netflix and is 
an API gateway to face requests!
Eureka which is developed by netflix is used to register and discover services.
note that the problem with this architecture is the fact that
zuul is a single point of failure but is a quick
approach to handle microservice architecture!

Test:
1-start eureka server
2-start zuul server
3-start eureka client
then go to :
http://localhost:8762/spring-cloud-eureka-client/greeting

you will receive:
service from 'SPRING-CLOUD-EUREKA-CLIENT with Port Number 8081'!

note :
 8762 is the zuul port 
 8761 is eureka port
 8081 is the service port

 
 
 