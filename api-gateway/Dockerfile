FROM openjdk:11.0.2-jre-slim
EXPOSE 8080
ARG JAR_FILE=*.jar
COPY ${JAR_FILE} app.jar
CMD ["java", "-jar", "app.jar"]
# docker build -t eunrcn/api-gateway:1.0.0 ./api-gateway