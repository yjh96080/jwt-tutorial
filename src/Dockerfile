FROM openjdk:17-alpine

ARG JAR_FILE=/build/libs/yjh96080-0.0.1-SNAPSHOT.jar

COPY ${JAR_FILE} /yjh96080.jar

ENTRYPOINT ["java","-jar","-Dspring.profiles.active=prod", "/yjh96080.jar"]
