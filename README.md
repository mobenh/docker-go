# Docker with Go
In this project I used Docker with a simple Go project.

## Technologies Used
* Go
* Docker

## Dependencies

* Install Go - https://go.dev/doc/install
* Install Docker - https://docs.docker.com/get-docker

## Executing program
* Download the repository to your computer and go to project file
```
git clone https://github.com/mobenh/docker-go
cd docker-go
```
* Run Docker file
```
docker build -t docker-test .
```
* Check image
```
docker image ls
```
* Run project
```
docker run -p 8080:8081 -it docker-test
```
* Go to browser and type localhost:8080 it should say: Hello, "/"
* Type localhost:8080/hi and it should say: Hi
