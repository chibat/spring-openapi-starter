# Spring Boot + OpenAPI Specification Starter

## Run

```
./gradlew bootRun
```

## Build

```
./gradlew bootRepackage
```

## initialization log

```
$ curl https://start.spring.io/starter.tgz -d dependencies=web,jdbc,security,actuator,h2 -d type=gradle-project -d baseDir=spring-openapi-starter -d groupId=app -d artifactId=appname -d name=appname | tar -xzvf -
$ cd spring-openapi-starter
$ rmdir src/main/resources/templates
$ mkdir src/main/java/app/appname/{web,service,domain}
$ mkdir eclipse
$ echo '# spring-openapi-starter' > README.md
$ git init
$ git add .
$ git commit -m "first commit"
```
