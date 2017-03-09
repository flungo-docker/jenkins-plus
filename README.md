# Jenkins Plus

An extension of the official [Jenkins docker image](https://hub.docker.com/_/jenkins/) providing additional tools and utilities installed to assist with builds. This is based on the alpine tag of the Jenkins image and adds the following packages:

- cloc
- graphviz

Unless you need these tools, the Jenkins image from the docker library should satisfy your needs.

## Build

To build this docker image, simply run:

```
docker build -t flungo/jenkins-plus:alpine src/alpine
```

## Usage

This image should be used in the same was as the [Jenkins docker image](https://hub.docker.com/_/jenkins/) from the library changing the image to `flungo/jenkins-plus`.
