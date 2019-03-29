FROM openjdk:11-jre-slim
RUN mkdir /app
COPY target/lib /app/lib
COPY target/*-runner.jar /app/application.jar
EXPOSE 80
CMD ["java", "-jar", "/app/application.jar"]

