---
title: Evolution Stage 0.2 AKA Deploy - classic
description: Getting started with DevOps
slug: "milestone-02"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 9
---


## GOAL
Deploy your app and it’s dependencies on a free tier EC2 instance with Ubuntu 20.

## ACCEPTANCE CRITERIA
+ The deployment should persist instance restarts.
+ The app data should persist instance restarts.
+ The final app deployment should not run in development mode.
+ The app server should be listening on port 80, and the server IP should be publicly reachable.
+ Conduct a load test with [Artillery](https://github.com/artilleryio/artillery) from your PC.