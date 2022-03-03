> This project is currently a work in progress, I have to migrate and update the packages as well as making the docker images smaller. They were too large, coming in at 1GB for just a simple image rest api.

# Udacity
## Cloud Developer Nanodegree Program
### Udagram (Microservices) app

## Getting Started

### Requirements

1. Kubectl
2. Docker
3. eksctl
4. AWS CLI

### Docker usage

`docker build . -t <DOCKER_USERNAME>/reverseproxy`

`docker-compose -f deployment/docker/docker-compose-build.yaml build`

### Create a Kubernetes cluster with eksctl