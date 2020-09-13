FROM openjdk:11.0.7-jre-slim
WORKDIR usr/src
ARG car_client
ARG car_secret
ENV CAR_SERVICE_CLIENT=$car_client
ENV CAR_SERVICE_SECRET=$car_secret
COPY ./target/ca*.jar /usr/src/car-service.jar
CMD ["java", "-jar", "car-service.jar"]