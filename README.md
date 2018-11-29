# FWMT Docker
This repository contains the docker-compose for FWMT that can be used to set up the environment for local development. This will spin up Job-service-v2, RM-adapter, TM-mock and rabbitMQ.

## Running Services Through Docker
To start all services through docker run `docker-compose up -d` this will spin up all services locally on the default ports.

## View service logs
To view the logs for one of the running services run `docker logs` followed by the container name e.g `docker logs job`
