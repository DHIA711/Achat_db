FROM openjdk:8-jdk-alpine
EXPOSE 8089
ARG JAR_FILE=target/achat-1.0.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]

#tn.esprit.rh.achat.AchatApplication "v2"