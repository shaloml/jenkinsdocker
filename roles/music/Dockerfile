FROM frolvlad/alpine-oraclejdk8:slim
WORKDIR /app
COPY ./roles/music/spring-music.jar /app/spring-music.jar
EXPOSE 8080
CMD java -jar -Dspring.profiles.active=none /spring-music.jar

