FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /tmp/app.jar
EXPOSE 9091
ENTRYPOINT ["java","-jar","/tmp/app.jar"]