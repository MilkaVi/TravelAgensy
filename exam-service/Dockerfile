FROM openjdk:17-alpine as java
ARG JAR_FILE=*.jar
COPY ${JAR_FILE} app.jar
ENV CONFIG_SERVER_URL=""
ENV CONFIG_EUREKA_URL=""
ENV KAFKA_BOOTSTRAP_SERVER=""
CMD ["sleep", "60"]
ENTRYPOINT ["java","-jar","/app.jar"]