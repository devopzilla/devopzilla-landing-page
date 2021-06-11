---
title: Evolution Stage 0.3 AKA Deploy - dockerized
description: Getting started with DevOps
slug: "milestone-03"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 8
images:
- "/events/devops-bootcamp-2021-1/charmander_2_final.png"
---


## GOAL
Dockerize your application and it’s dependencies, then deploy the containers on another free tier EC2 instance with Ubuntu 20.

## ACCEPTANCE CRITERIA
+ Create Dockerfiles for your app.
+ Add resource constraints to each docker container.
+ Push your docker image to a Docker image registry.
+ Deploy your app and it’s dependencies using docker-compose.
+ Any new resources you add (etc. Dockerfile, docker-compose.yaml) should be commited to the source code.
+ Make sure that your app and it’s data persist restarts.
+ The app server should be listening on port 80, and the server IP should be publicly reachable.
+ The final app deployment should not run in development mode.
+ Conduct a load test from your PC.

## DELIVERABLES 📦
+ Github project link (the project should be public)
+ Docker Hub repository link (the repo should be public)
+ Public server IP v4 address
+ Short demo video posted on Slack
    + show how the app is deployed on the server
    + explain the server restart persistence mechanism
    + show load testing run
+ Load testing reports in text files on the repo, inside the dir "load_test_reports/load_test_{milestone number}"


## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Docker Registry|[Docker Hub Registry](https://docs.docker.com/docker-hub/repos/)|
|Running Containers|[Docker Compose](https://docs.docker.com/compose/)|
|Docker Resource Constraints|[Docker Resource Constraints](https://docs.docker.com/config/containers/resource_constraints/)|
|Load Testing|[Artillery](https://github.com/artilleryio/artillery)|
