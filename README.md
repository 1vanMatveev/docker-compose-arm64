# docker-compose-arm64

FROM amazoncorretto:17

..

CMD ["java", "-Dcom.sun.management.jmxremote", "-jar", "service.jar"]
