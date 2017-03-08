## Spring Boot App Protection

This fork of the simple web application (https://github.com/StringerJavaObfuscator/gs-spring-boot) with Spring Boot is to demonstrate how to Stringer protection for this kind of applications.

## Description
- https://jfxstore.com/stringer/docs#maven-plugin
- https://jfxstore.com/stringer/docs#gradle-plugin

## Requirements
- Maven or Gradle
- Stringer Standard or Enterpise with a valid license

## Configuring 
- Maven: install Stinger and Stringer Maven plugin to local Maven repository:

```
mvn install:install-file -Dfile=`pwd`/stringer.jar -DpomFile=`pwd`/stringer.pom
mvn install:install-file -Dfile=`pwd`/stringer-annotations.jar -DpomFile=`pwd`/stringer-annotations.pom
mvn install:install-file -Dfile=`pwd`/stringer-maven-plugin.jar -DpomFile=`pwd`/stringer-maven-plugin.pom
```

- Gradle: install Stinger and Stringer Gradle plugin to local Maven repository::

```
mvn install:install-file -Dfile=`pwd`/stringer.jar -DpomFile=`pwd`/stringer.pom
mvn install:install-file -Dfile=`pwd`/stringer-annotations.jar -DpomFile=`pwd`/stringer-annotations.pom
mvn install:install-file -Dfile=`pwd`/stringer-gradle-plugin.jar -DpomFile=`pwd`/stringer-gradle-plugin.pom
```

## Building

```
mvn clean install
```
or 

```
./gradlew install
```
