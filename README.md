# Read me
The original idea is from  
https://medium.com/@sehgal.mohit06/actuator-in-spring-boot-application-1c8b28c28366

http://localhost:8081/actuator/beans

It shows all the beans from our spring boot application.
Beans details like its scope, type, aliases, resource(class) and dependencies are exposed.

# Start up
The original idea is from  
https://medium.com/tuanhdotnet/ways-to-speed-up-spring-boot-application-startup-time-8c9b56435095

This shows a detailed breakdown of the startup process, showing the initialization time for each bean, which can help you identify and resolve performance bottlenecks.
curl http://localhost:8080/actuator/startup
