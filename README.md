# spring-boot-cloud-config-server
  This is a sample project to expose your properties used by your spring boot application through Spring Boot Cloud Config Server.<br />

# Properties used in application.properties
  server.port=61004<br />
  spring.application.name=spring-boot-cloud-config-server<br />
  server.servlet.context-path=/spring-boot-cloud-config-server<br />
  spring.profiles.active=native<br />
  spring.cloud.config.server.native.searchLocations=file:///C:/Users/SpringBootCloudConfigServer/src/main/resources/config<br />
  spring.cloud.config.server.bootstrap=false<br />

# Enabling security:
  spring.security.user.name=root<br />
  spring.security.user.password=s3cr3t<br />
