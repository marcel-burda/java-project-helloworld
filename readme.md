# This is my first Java Hello World App

Everybody started small...

Reference:
https://spring.io/guides/gs/maven/

## Needed software

- Java JDK 8 or higher
- Maven
- setting env variables correctly for both

## How to compile

Simply run 
```
mvn compile
```
to build your project.

To get executeable jar files you have to run 
```
mvn package
```
and to run the tests run the following:
```
mvn test
```

## Run the program

In the target dir you find your executables. Run them with:
```
java -jar target/gs-maven-0.1.0.jar
```