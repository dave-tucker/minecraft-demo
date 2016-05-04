# minecraft-demo
Multi-Server Minecraft Worlds with Docker

NOTE: Requires Docker 1.9 or later

## Single host usage (for development):

Note: your machine will need at least 5GB RAM

```
./build_containers
docker-compose up
```

## Multi-host usage (using swarm):

You can create some machines using Digital Ocean and Docker Machine using
```
./machines
```
This was exactly what I used for the demo at DockerCon EU

```
./build_containers swarm
docker-compose up
```
