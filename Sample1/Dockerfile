FROM openjdk:9-jre
VOLUME /tmp
ADD greeting-1.2.jar app.jar
EXPOSE 8080/tcp
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
