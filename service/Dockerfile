FROM openjdk:8-jre-alpine
EXPOSE 6883
ADD /target/oauth2-service.jar server.jar
CMD ["/bin/sh","-c","java -Dlight-4j-config-dir=/config -Dlogback.configurationFile=/config/logback.xml -jar /server.jar"]