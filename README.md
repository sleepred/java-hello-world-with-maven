![example workflow](https://github.com/enlena615/java-hello-world-with-maven/actions/workflows/maven.yml/badge.svg) 
![Actions Status](https://github.com/enlena615/java-hello-world-with-maven/actions/workflows/maven.yml/badge.svg)
[![Build Status](https://ci.spring.io/api/v1/teams/spring-framework/pipelines/spring-framework-5.3.x/jobs/build/badge)](https://ci.spring.io/teams/spring-framework/pipelines/spring-framework-5.3.x?groups=Build")
[![Actions Status](https://github.com/enlena615/java-hello-world-with-maven/actions/workflows/maven.yml/badge.svg)](https://github.com/enlena615/java-hello-world-with-maven/actions)


# java-hello-world-with-maven
Hello World sample with Java with Maven

## Compile

```
$ mvn compile
```

## Test

```
$ mvn test
```

## Run

```
$ mvn exec:java
```

## Package

```
$ mvn package
```

## Creating this project by Maven

```
$ mvn archetype:generate \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DinteractiveMode=false \
  -DgroupId=io.openlena.lab.hello \
  -DartifactId=openlena_hello
```

