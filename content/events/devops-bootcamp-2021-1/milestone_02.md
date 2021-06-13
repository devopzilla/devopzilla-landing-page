---
title: Evolution Stage 0.2 AKA Deploy - classic
description: Getting started with DevOps
slug: "milestone-02"
type: post
date: 2021-06-13
publishdate: 2021-06-13
weight: 9
images:
- "/events/devops-bootcamp-2021-1/charmander_2_final.png"
---


## GOAL
Deploy your app and it’s dependencies on a free tier EC2 instance with Ubuntu 20.

## ACCEPTANCE CRITERIA
+ The deployment should persist instance restarts.
+ The app data should persist instance restarts.
+ The final app deployment should not run in development mode.
+ The app server should be listening on port 80, and the server IP should be publicly reachable.
+ Conduct a load test with [Artillery](https://github.com/artilleryio/artillery) from your PC.
    + Start with 10 RPS (Requests/Second)
    + Double the number of requests per second until you reach failures from the server. (Server limit)
    + Export and attach the artillery reports to the repository.


## DELIVERABLES 📦
+ Github project link (the project should be public)
+ Public server IP v4 address
+ Short demo video posted on Slack
    + show how the app is deployed on the server
    + explain the server restart persistence mechanism
    + show load testing run
+ Load testing reports in text files on the repo, inside the dir "load_test_reports/load_test_{milestone number}"

## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Amazon Web Services|[AWS free tier services](https://aws.amazon.com/free)|
|Process Persistence|[Linux systemd services](https://everyday.codes/linux/services-in-systemd-in-depth-tutorial/)|
|Django|[Production environment](https://www.digitalocean.com/community/tutorials/how-to-set-up-django-with-postgres-nginx-and-gunicorn-on-ubuntu-20-04)|
|Flask|[Production environment](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-20-04)|
|Postgresql|[Setup and use](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart)|