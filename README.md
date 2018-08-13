# api-collab-server
[![Build Status](https://travis-ci.org/api-collab/api-collab-server.png)](https://travis-ci.org/api-collab/api-collab-server)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=io.apicollab%3Aserver&metric=alert_status)](https://sonarcloud.io/dashboard?id=io.apicollab%3Aserver)


## Building with docker

First build the jar file using
```
mvn package
```

Next build the docker images using
```
docker-compose build
docker-compose up
```


http://localhost:8000/api/applications