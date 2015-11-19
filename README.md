# minecraft-demo
Multi-Server Minecraft Worlds with Docker

NOTE: Requires Docker 1.9 or later

## Single host usage (for development):

Note: your machine will need at least 5GB RAM

```
./build_containers
docker-compose --x-networking up
```

## Multi-host usage (using swarm):

```
./build_containers swarm
docker-compose --x-networking up
```
