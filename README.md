### Contents ###
[Top](#top)

1. [Build](#build)
1. [Testing](#testing)
1. [Sonar](#sonar)
1. [Code Coverage](#coverage)
1. [JSON Validation](#json-validation)
1. [CRA REST Service](#cra-rest-service)
1. [CRA Setup](#cra-setup)
1. [CRA Setup Angular](#cra-setup-angular)
1. [Eclipse Setup](#eclipse-setup)
1. [Tomcat Setup](#tomcat-setup)
1. [Postman Setup](#postman-setup)

### Build ###

Maven: Builds REST Service & Angular Project 
```xml
	<modules>
		<module>domain</module>
		<module>email-service</module>
		<module>dao-jpa-impl</module>
		<module>services</module>
		<module>service-impl</module>
		<module>api</module>
		<module>apps</module>
	</modules>
```

Maven Build: Commands
```xml
mvn clean install  - for complete build (will not run integration tests)

mvn install -Dmaven.test.skip=true (to skip unit tests)

```

[Top](#top)

### Testing ###

Integration Tests: To run integration tests from command line
```xml
mvn integration-test -P integration

mvn integration-test -P integration -Dserver.port=8081 -Dserver.host=http://localhost   - this command you can use if the host or port number is different from default.
```

[Top](#top)

### Sonar ###

Integration Tests: To run integration tests from command line
```xml
mvn clean install 

mvn sonar:sonar 

or 

mvn clean verify sonar:sonar	
```

[Top](#top)


### Code Coverage ###


[Top](#top)

### JSON Validation ###


[Top](#top)


### CRA REST Service ###


[Top](#top)

### CRA Setup ###


[Top](#top)

### CRA Setup Angular ###

[Top](#top)


### Eclipse Setup ###


[Top](#top)

### Tomcat Setup ###

[Top](#top)


### Postman Setup ###

[Top](#top)
