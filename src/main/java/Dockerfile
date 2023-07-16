FROM openjdk:17
RUN mkdir -p /app/
ADD build/libs/pizarron-0.0.1-SNAPSHOT.jar /app/pizarronAPI.jar
ENTRYPOINT [ "java", "-jar", "/app/pizarronAPI.jar" ]