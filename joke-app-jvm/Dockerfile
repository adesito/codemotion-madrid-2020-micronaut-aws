FROM openjdk:14-alpine
COPY build/libs/joke-*-all.jar joke.jar
EXPOSE 8080
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "joke.jar"]