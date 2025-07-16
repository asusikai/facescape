FROM openjdk:11
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} facescape.jar
ENTRYPOINT ["java", "-jar", "facescape.jar"]
