---
title: Evolution Stage 0.3 AKA Deploy - dockerize
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
+ Deploy your app and it’s dependencies using docker-compose.
+ Make sure that your app and it’s data persist restarts.
+ The app server should be listening on port 80, and the server IP should be publicly reachable.
+ The final app deployment should not run in development mode.
+ Conduct a load test with [Artillery](https://github.com/artilleryio/artillery) from your PC.