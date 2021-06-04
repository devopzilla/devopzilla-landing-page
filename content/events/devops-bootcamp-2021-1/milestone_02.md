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

## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Amazon Web Services|[AWS free tier services](https://aws.amazon.com/free)|
|Process Persistence|[Linux systemd services](https://everyday.codes/linux/services-in-systemd-in-depth-tutorial/)|
|Django|[Production environment](https://www.digitalocean.com/community/tutorials/how-to-set-up-django-with-postgres-nginx-and-gunicorn-on-ubuntu-20-04)|
|Flask|[Production environment](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-20-04)|
|Postgresql|[Setup and use](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart)|