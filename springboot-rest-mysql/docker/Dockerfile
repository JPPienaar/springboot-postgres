FROM openjdk:8-jdk-alpine

RUN apk update && apk add ca-certificates wget && update-ca-certificates

ADD spring-rest-mysql*.jar /spring-rest-mysql.jar

CMD ["java", "-jar", "/spring-rest-mysql.jar"]

EXPOSE 8080