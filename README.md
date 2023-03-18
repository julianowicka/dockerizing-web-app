### Dockerizing a node.js web app

#### This example show how to get a node.js application into a docker container

### Scripts

#### Building image
```
docker build . -t julianowicka/docker-image
```
#### Runt the image
```
docker run -p 9000:8080 -d julianowicka/docker-image
```
#### Shut down the image
```
docker kill <container id>
```