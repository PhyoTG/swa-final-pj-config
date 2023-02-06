# swa-final-pj-config
SWA Final Project Config Jan 2023

# To Implement From Service
Add Below Dependencies to POM file

   <dependencies>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
        <dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-starter-config</artifactId>
        </dependency>
        <dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-starter-bootstrap</artifactId>
        </dependency>
    </dependencies>
   
   
# Create Application.yml 
Put Server Port

# Create bootstrap.yml
spring:
  application:
    name: SchoolService #your service name
  cloud:
    config:
      url: http://localhost:8888 #config-server url
