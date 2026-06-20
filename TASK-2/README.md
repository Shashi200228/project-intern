# Task 2 – Docker Deployment

## Objective

Deploy web application inside Docker container.

## Docker Installation

sudo apt install docker.io -y

## Build Docker Image

docker build -t mywebapp .

## Run Container

docker run -d -p 8000:80 --name webcontainer mywebapp

## Dockerfile Used

FROM nginx

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx","-g","daemon off;"]

## Verification

docker ps

Application accessible on:

http://SERVER_IP:8000

## Result

Dockerized application successfully deployed.
