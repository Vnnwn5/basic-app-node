# basic-app-node

## Prerequisites

- Docker version 20.10.21

### Installing

Clone the repository:

`git clone https://github.com/Vnnwn5/basic-app-node.git`

Install Docker:

`https://docs.docker.com/get-docker/`

Start app with Docker:

`docker build . -t <name image>` -create an image-
`docker images` -verify your new created image-
`docker run -p <localport>:80 --name <name container> -it <name image>`
`docker ps` -verify that your container is working-
`go to -localhost:<localport>-`

## Its a basic app using node to practice creating Docker images.


