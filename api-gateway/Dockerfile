FROM openjdk:11.0.7-jre-slim
WORKDIR usr/src
ARG gateway_client
ARG gateway_secret
ENV API_GATEWAY_CLIENT=$gateway_client
ENV API_GATEWAY_SECRET=$gateway_secret
COPY ./target/api*.jar /usr/src/gateway.jar
CMD ["java", "-jar", "gateway.jar"]
