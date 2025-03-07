FROM openjdk:17

WORKDIR /app

COPY fibonacci.java /app/

RUN javac fibonacci.java

CMD ["java", "fibonacci"]
