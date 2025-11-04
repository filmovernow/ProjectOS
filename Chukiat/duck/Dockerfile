FROM alpine/java:21.0.4-jdk
WORKDIR /server
COPY KMUTTMessageSystem.jar server.jar

EXPOSE 1669
EXPOSE 8080
ENTRYPOINT ["java" , "-jar" , "server.jar"]