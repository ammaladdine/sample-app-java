FROM openjdk:11-jre-slim
RUN mkdir apps
COPY target/original-loadgen-0.9.0-SNAPSHOT.jar  /apps
WORKDIR /apps
EXPOSE 50050
ENTRYPOINT ["java", "-jar", "original-loadgen-0.9.0-SNAPSHOT.jar"]
