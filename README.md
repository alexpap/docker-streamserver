# docker-streamserver

* Install  [docker] (https://docs.docker.com/engine/installation/)
    
* Running

```
cd docker-streamserver
docker build -t streamserver .
docker run -i -t --rm -P --name streamserver streamserver
```

* Access container

```
docker exec -t -i streamserver /bin/bash
```
