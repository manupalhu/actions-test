FROM openjdk:19-jdk-alpine3.16


COPY ../*.jar ./

WORKDIR /


EXPOSE 8080


CMD java -jar ${{ secrets.jar }}.jar
