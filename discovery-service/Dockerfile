FROM openjdk:11.0.7-jre-slim
WORKDIR usr/src
COPY ./target/dis*.jar /usr/src/discovery.jar
CMD ["java", "-jar", "discovery.jar"]