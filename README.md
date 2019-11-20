# go-dock
Go in Docker

`go-dock` is a simple Go server that server a single sample endpoint and is running in a Docker container. Whenever projects is updated the code is automatically recompiled and run in the docker image.

## Usage
To start the Docker container run
```
docker-compose up
```
Then visit `localhost:8080` in your browser to view the sample API.
