# Testing NATS

Codebase based on [this](http://nats.io/blog/docker-compose-plus-nats) tutorial.

```
docker-compose -f build.yml build
docker-compose -f build.yml up
curl localhost:8080/createTask
```
