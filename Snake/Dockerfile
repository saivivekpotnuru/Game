FROM openjdk:8
COPY ./src/SnakeGame.java /tmp
WORKDIR /tmp
RUN ["javac","SnakeGame.java"]
ENTRYPOINT ["java","SnakeGame"]