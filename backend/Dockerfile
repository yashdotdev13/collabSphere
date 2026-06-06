FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY target/*.jar app.jar

EXPOSE 8090

ENTRYPOINT ["java","-jar","app.jar","--spring.profiles.active=docker"]