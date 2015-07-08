# spring-boot
Experimenting with spring boot

Requires
* jdk 1.7
* gradle 2.3+

### build
```shell
gradle build
```
### run
```shell
java -jar build/libs/gs-spring-boot-0.1.0.jar
```
### test
Webapp:
[http://localhost:8080/](http://localhost:8080/) ==> Greetings from Spring Boot!

Actuator:
[http://localhost:8080/health](http://localhost:8080/health) ==> {"status":"UP"}
