FROM openjdk
RUN mkdir app
WORKDIR app
COPY ./target/*.jar /app/admin-server.jar
CMD ["java","-jar","/app/admin-server.jar"]
