# TODO

#FROM ubuntu
#COPY ./ /app

#ENTRYPOINT ["echo"]

FROM openjdk:17
EXPOSE 8080
#your jar file
COPY /build/libs/books-0.0.1-SNAPSHOT.jar /myBookApp.jar

#ADD target/
#
ENTRYPOINT ["java","-jar","myBookApp.jar"]
#in entrypoint you specify the command to run the jar ??