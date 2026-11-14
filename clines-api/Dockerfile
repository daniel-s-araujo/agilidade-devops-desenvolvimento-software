FROM eclipse-temurin:11-jre-jammy

WORKDIR /clines

COPY target/*.jar /clines/app.jar

EXPOSE 8080

CMD java -XX:+UseContainerSupport -jar app.jar
