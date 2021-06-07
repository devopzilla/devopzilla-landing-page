---
title: Evolution Stage 0.3 AKA Deploy - dockerized
description: Getting started with DevOps
slug: "milestone-03"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 8
---


## GOAL
Dockerize your application and it’s dependencies, then deploy the containers on another free tier EC2 instance with Ubuntu 20.

## ACCEPTANCE CRITERIA
+ Create Dockerfiles for your app.
+ Push your docker image to a Docker image registry.
+ Deploy your app and it’s dependencies using docker-compose.
+ Any new resources you add (etc. Dockerfile, docker-compose.yaml) should be commited to the source code.
+ Make sure that your app and it’s data persist restarts.
+ The app server should be listening on port 80, and the server IP should be publicly reachable.
+ The final app deployment should not run in development mode.
+ Conduct a load test from your PC.


## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Docker Registry|[Docker Hub Registry](https://docs.docker.com/docker-hub/repos/)|
|Running Containers|[Docker Compose](https://docs.docker.com/compose/)|
|Load Testing|[Artillery](https://github.com/artilleryio/artillery)|
