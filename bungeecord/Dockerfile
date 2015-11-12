FROM java:8
WORKDIR /usr/src/bungee
RUN wget -q http://ci.md-5.net/job/BungeeCord/lastSuccessfulBuild/artifact/bootstrap/target/BungeeCord.jar
EXPOSE 25577
ADD config.yml /usr/src/bungee/
CMD ["java", "-jar", "BungeeCord.jar"]
