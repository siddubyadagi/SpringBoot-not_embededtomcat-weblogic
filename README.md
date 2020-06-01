# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.accurate.solutions.springboot-notomcat' is invalid and this project uses 'com.accurate.solutions.springbootnotomcat' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.3.0.RELEASE/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.3.0.RELEASE/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.3.0.RELEASE/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides

Project name: springboot-notomcat
Used: Spring boot 2.x
Java : 11.x
Build: maven
Server : Weblogic 14.x (Not Embaded tomcat)

http://localhost:7001/springboot/customer/1

{
"fname": "testa",
"lname": "testb",
"email": "test@gmail.com",
"id": 1
}


http://localhost:7001/springboot/customer/all


[
{
"fname": "testa",
"lname": "testb",
"email": "test@gmail.com",
"id": 1
},
{
"fname": "testb",
"lname": "testb",
"email": "testb@gmail.com",
"id": 1
},
{
"fname": "testc",
"lname": "testb",
"email": "testc@gmail.com",
"id": 1
},
{
"fname": "testd",
"lname": "testb",
"email": "testd@gmail.com",
"id": 1
},
{
"fname": "teste",
"lname": "testb",
"email": "teste@gmail.com",
"id": 1
}
]

http://localhost:7001/springboot/actuator


{
"_links": {
"self": {
"href": "http://localhost:7001/springboot-notomcat/actuator",
"templated": false
},
"beans": {
"href": "http://localhost:7001/springboot-notomcat/actuator/beans",
"templated": false
},
"caches-cache": {
"href": "http://localhost:7001/springboot-notomcat/actuator/caches/{cache}",
"templated": true
},
"caches": {
"href": "http://localhost:7001/springboot-notomcat/actuator/caches",
"templated": false
},
"health": {
"href": "http://localhost:7001/springboot-notomcat/actuator/health",
"templated": false
},
"health-path": {
"href": "http://localhost:7001/springboot-notomcat/actuator/health/{*path}",
"templated": true
},
"info": {
"href": "http://localhost:7001/springboot-notomcat/actuator/info",
"templated": false
},
"conditions": {
"href": "http://localhost:7001/springboot-notomcat/actuator/conditions",
"templated": false
},
"configprops": {
"href": "http://localhost:7001/springboot-notomcat/actuator/configprops",
"templated": false
},
"env": {
"href": "http://localhost:7001/springboot-notomcat/actuator/env",
"templated": false
},
"env-toMatch": {
"href": "http://localhost:7001/springboot-notomcat/actuator/env/{toMatch}",
"templated": true
},
"loggers": {
"href": "http://localhost:7001/springboot-notomcat/actuator/loggers",
"templated": false
},
"loggers-name": {
"href": "http://localhost:7001/springboot-notomcat/actuator/loggers/{name}",
"templated": true
},
"heapdump": {
"href": "http://localhost:7001/springboot-notomcat/actuator/heapdump",
"templated": false
},
"threaddump": {
"href": "http://localhost:7001/springboot-notomcat/actuator/threaddump",
"templated": false
},
"metrics-requiredMetricName": {
"href": "http://localhost:7001/springboot-notomcat/actuator/metrics/{requiredMetricName}",
"templated": true
},
"metrics": {
"href": "http://localhost:7001/springboot-notomcat/actuator/metrics",
"templated": false
},
"scheduledtasks": {
"href": "http://localhost:7001/springboot-notomcat/actuator/scheduledtasks",
"templated": false
},
"mappings": {
"href": "http://localhost:7001/springboot-notomcat/actuator/mappings",
"templated": false
}
}
}
