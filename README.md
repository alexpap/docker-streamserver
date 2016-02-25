# docker-streamserver

* Install  [docker] (https://docs.docker.com/mac/)
    
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
