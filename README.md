# docker-streamserver

* Install  [docker] (https://docs.docker.com/mac/)
    
* Running

    ```
    cd docker-streamserver
    docker build -t streamserver .
    docker run -i -t --rm -p 8989:8989 --name streamserver streamserver
    ```

* Access steams http://localhost:8989/measurements 
  (on linux use locahost, on win/mac use 'docker-machine ip')
   
* Access container

    ```
    docker exec -t -i streamserver /bin/bash
    ```
