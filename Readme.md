# Kafka-Docker-Setup

- clone this repo
- cd <cloned-directory>

```
docker compose up -d
```

and your container will be running

- once the container is running you can run this command to go to kafka cli

```
docker exec -it -w /opt/kafka/bin broker sh

```
