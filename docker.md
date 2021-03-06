
#### run maven
```
mvn spring-boot:run
mvn clean
mvn package
java -jar target/gs-maven-0.1.0.jar
```

#### dockerizing
```
docker build -t taixingbi/springboot-hello .
docker push taixingbi/springboot-hello
docker run --publish 8080:8080 taixingbi/springboot-hello
```

#### mvn

1. validate - validate the project is correct and all necessary information is available
2. compile - compile the source code of the project
3. test - test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed
4. package - take the compiled code and package it in its distributable format, such as a JAR.
verify - run any checks on results of integration tests to ensure quality criteria are met
5. install - install the package into the local repository, for use as a dependency in other projects locally
6. deploy - done in the build environment, copies the final package to the remote repository for sharing with other developers and projects.




