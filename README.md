### Dockerizing a node.js web app

#### This example show how to get a node.js application into a docker container

### Scripts

#### Building image
```
docker build . -t julianowicka/dockerizing-web-app
```
#### Runt the image
```
docker run -p 9000:8080 -d julianowicka/dockerizing-web-app
```
#### Shut down the image
```
docker kill <container id>
```