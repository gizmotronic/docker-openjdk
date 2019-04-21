# Supported tags and respective `Dockerfile` links

* `java8`, `latest`, `8u191` [(Dockerfile)](https://github.com/gizmotronic/docker-openjdk/blob/master/openjdk8/Dockerfile)

# Base Docker Image

* [ubuntu:18.04](https://registry.hub.docker.com/_/ubuntu/)

# Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/gizmotronic/openjdk/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull gizmotronic/openjdk`

### Usage

    docker run -it --rm gizmotronic/openjdk

#### Run `java`

    docker run -it --rm gizmotronic/openjdk java

#### Run `javac`

    docker run -it --rm gizmotronic/openjdk javac

# LICENSE

MIT
