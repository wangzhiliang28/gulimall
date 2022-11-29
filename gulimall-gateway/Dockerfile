FROM java:8

EXPOSE 8080

VOLUME /tmp
ADD target/*.jar lapp.jar

RUN bash -c 'touch /app.jar'

ENTRYPOINT ["java", "-jar", "/app.jar","--spring.profiles.active=prodn "]

