FROM alpine/java:21.0.4-jdk
WORKDIR /server
COPY KMUTTMessageSystemClient.jar server.jar

ENTRYPOINT ["java" , "-jar" , "server.jar"]