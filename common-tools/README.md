Docker image that contains typical tooling within on a unix workstation.  Includes the following on an ubuntu base image:
1. yq
1. jq
1. vim
1. git

Build docker image (from the top directory):
 `docker build -f common-tools/Dockerfile.common-tools.build -t common-tools .`
