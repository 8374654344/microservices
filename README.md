# microservices
microservices in spring cloud tools
creation of eureka server
=========================
create spring boot project from start.spring.io
================================================
add the dependency as eureka server
and starter web
================================================
configure in application.properties file like below
spring.application.name=service-registry
server.port=8761
eureka.instance.hostname=localhost
eureka.client.fetch-registry=false
eureka.client.register-with-eureka=false
