FROM adoptopenjdk/openjdk11:alpine-jre

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} creditMovement.jar
ENTRYPOINT ["java","-jar","/creditMovement.jar"]
