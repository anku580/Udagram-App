# Udagram-App

This is basically a web application built on ionic and node.js. There are two microservices implemented in this application.

## How to run?

You nedd to first create docker images of each of the project folder.
> docker build -t {docker_username}/{image_name}

After creating images, please switch to the `docker` folder inside `udacity-c3-deployment` and then run the following command
> docker-compose up

## CD

The CD tool used here is travis. A new commit to this repository will create an automatic build.

### Images in DockerHub

* 9876556200/udacity-frontend
* 9876556200/udacity-restapi-user
* 9876556200/udacity-restapi-feed