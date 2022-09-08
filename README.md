# MVN-SPRING-STARTER
Meant to be a good example of a Maven Spring Boot project for beginners that is tested bottom-up, starting with unit
tests. The unit tests, by nature, may mock certain
parts of the system and test within a black box.

# How-To Manually Deploy WAR

1. Using Maven, run 'mvn clean package' to build the .war file.
2. Then, place the .war in your Tomcat webapps dir.
3. Navigate locally to http://localhost:8080/

# Running just the Unit Tests

1. Using Maven, run 'mvn test'
