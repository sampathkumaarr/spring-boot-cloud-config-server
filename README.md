# spring-boot-cloud-config-server
  This is a sample project to expose your properties used by your spring boot application through Spring Boot Cloud Config Server.

# Properties used in application.properties
  server.port=61004
  spring.application.name=spring-boot-cloud-config-server
  server.servlet.context-path=/spring-boot-cloud-config-server
  spring.profiles.active=native
  spring.cloud.config.server.native.searchLocations=file:///C:/Users/SpringBootCloudConfigServer/src/main/resources/config
  spring.cloud.config.server.bootstrap=false

# Enabling security:
  spring.security.user.name=root
  spring.security.user.password=s3cr3t 
