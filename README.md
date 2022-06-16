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

