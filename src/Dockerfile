FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY . .

RUN javac -d . *.java

CMD ["java", "Main"]