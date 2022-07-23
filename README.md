# Docker for Pocketbase

## Image

´´´
docker build -t pocketbase:0.3.2 --build-arg PB_VERSION=0.3.2 .
´´´

## Run

´´´
docker run --name pocketbase -it -p 8090:8090 pocketbase:0.3.2
´´´
