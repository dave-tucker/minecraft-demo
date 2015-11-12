FROM java:8
WORKDIR /usr/src/myserver
ADD server.properties server.properties
ADD spigot.yml spigot.yml
ADD bukkit.yml bukkit.yml
ADD plugins plugins
RUN echo eula=true > eula.txt
VOLUME /usr/src/myserver
