FROM openjdk:17
ENV APP_HOME=/usr/app
WORKDIR $APP_HOME
COPY /target/*.jar app.jar
EXPOSE 8082
CMD ["java", "-jar", "app.jar"]
