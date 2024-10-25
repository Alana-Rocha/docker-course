Commands Docker:

docker build -t app .
docker build -t app:v1.0.0 .
docker image remove app:v1.0.0 
docker images

*Rename Image Tag*
docker image tag app:latest app:v1.0.0

*Repository*
docker login
docker push alanarocha/app:v1

*Create a new Docker image in the repository*
The push refers to repository [docker.io/alanarocha/app]