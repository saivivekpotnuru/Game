FROM openjdk:8
EXPOSE 8080
COPY Snake/src/SnakeGame.java /tmp
WORKDIR /tmp
RUN ["javac","SnakeGame.java"]
ENTRYPOINT ["java","SnakeGame"]