
## How to build

Build with Gradle wrapper:

```sh
$ ./gradlew clean build
```

## How to run

Run with Gradle wrapper:

```sh
$ ./gradlew bootRun
```

Or run it as an executable jar:

```sh
$ java -jar build/libs/spring-boot-boilerplate-0.1.0.jar
```

## Testing with Curl

```sh
$ curl http://localhost:8080/hello
{"message":"Hello, World!"}
```
