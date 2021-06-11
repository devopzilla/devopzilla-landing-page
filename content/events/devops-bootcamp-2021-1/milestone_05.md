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

## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|||
