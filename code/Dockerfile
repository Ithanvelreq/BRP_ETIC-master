FROM openjdk:7
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac ./BRP_back_end/src/main/java/fr/etic/brp/brp_back_end/ihm/console/Main.java
CMD ["java", "Main"]
