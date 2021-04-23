# Common Tools Docker Image

Docker image with typical tooling of a unix workstation.  Includes the following packages on an ubuntu 20.04 base image:
1. yq
1. jq
1. vim
1. git
1. python 3.8
1. pip3

Build docker image (from the top directory):
 `docker build -f common-tools/Dockerfile.common-tools.build -t common-tools .`

 This docker image is built and pushed [here](https://hub.docker.com/repository/docker/medoror/common-tools)
