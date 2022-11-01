# DevOps course docker homework

NodeJS hello-world application in docker container.
Link: [Docker Hub repository](https://hub.docker.com/repository/docker/koziuberda/docker-lab)

## Build
    docker build -t koziuberda/docker-lab:1.1 .

## Run the app
    docker run -d --rm --name devops-nodejs --cpus="1" --memory="64M" -p 80:80 koziuberda/docker-lab:1.1

## Results
    localhost
