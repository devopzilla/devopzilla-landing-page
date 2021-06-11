---
title: Evolution Stage 0.5 AKA Scalability
description: Getting started with DevOps
slug: "milestone-05"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 6
images:
- "/events/devops-bootcamp-2021-1/charmander_2_final.png"
---


## GOAL
Handle higher traffic loads by scalling the app hosizontally. To achieve horizontal scalability the app will be deployed across multiple EC2 instances.

## ACCEPTANCE CRITERIA
+ Create two EC2 machines and deploy two instances of the app on them.
+ Create once EC2 machine for the load balancer (NGINX as a reverse proxy in our case). NGINX instance should be dockerized.
+ Create once EC2 machine for the database. Database instance should be dockerized.
+ Configure the load balancer to route traffic to the two instances in a round robin fashion.
+ Update your CI/CD to deploy the instances on different machines.

## DELIVERABLES 📦
+ Github project link (the project should be public)
+ Docker Hub repository link (the repo should be public)
+ Public server IP v4 address
+ Short demo video posted on Slack
    + show how the app is deployed
    + explain the app architecture
    + explain how the CI/CD pipeline changed
    + explain the server load balancing mechanism
    + show load testing run
+ Load testing reports in text files on the repo, inside the dir "load_test_reports/load_test_{milestone number}"


## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Load Balancing|[Nginx Docker Load Balancing (LB strategies)](https://levelup.gitconnected.com/nginx-load-balancing-and-using-with-docker-7e16c49f5d9)|
|Load Balancing|[Nginx Docker Load Balancing](https://towardsdatascience.com/sample-load-balancing-solution-with-docker-and-nginx-cf1ffc60e644)|
|Inter-server communication|[AWS EC2 Security Groups](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/security-group-rules-reference.html)|
