FROM adoptopenjdk/openjdk12
ADD target/dockersample.jar /usr/app/
WORKDIR /usr/app
EXPOSE 8085
ENTRYPOINT ["java", "-jar","dockersample.jar"]																																											