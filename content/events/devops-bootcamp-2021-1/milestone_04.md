---
title: Evolution Stage 0.4 AKA CI/CD
description: Getting started with DevOps
slug: "milestone-04"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 7
---


## GOAL
Automate the whole process of shipping application changes to production.


## ACCEPTANCE CRITERIA
+ The automation pipeline should be triggered on code changes to master
+ The pipeline should run the code's automated tests
+ The pipeline should re-build the docker image and push it to your docker repository
+ The pipeline should re-deploy the application on the EC2 instance
+ Secrets like SSH private keys should not be visible in source code nor printed in pipeline logs.

## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Github Actions|[Github Actions Course](https://lab.github.com/githubtraining/github-actions:-hello-world)|
|Github Actions|[Action to build and push images](https://github.com/marketplace/actions/build-and-push-docker-images)|
|Github Actions|[Action to copy code to production server](https://github.com/marketplace/actions/ssh-deploy)|