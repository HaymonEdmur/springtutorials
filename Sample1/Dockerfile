FROM openjdk:9-jre
VOLUME /tmp
EXPOSE 8080/tcp
ADD greeting-1.2.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
