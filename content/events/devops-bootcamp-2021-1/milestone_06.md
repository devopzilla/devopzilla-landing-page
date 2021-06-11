---
title: Evolution Stage 1.0 AKA Quick intro to Kubernetes
description: Getting started with DevOps
slug: "milestone-06"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 5
images:
- "/events/devops-bootcamp-2021-1/charmander_2_final.png"
---


## GOAL
Congratulation you just evolved into Charmeleon! It's time to try out kubernetes by building a small dev cluster on your machines. This is the first step into evolving to Charizard!

Keep in touch with us to know more about our next "Charmeleon-to-Charizard" Bootcamp.

## ACCEPTANCE CRITERIA
+ Create kubernetes manifests for our application.
    + Deployment Resource to run 2 replicas of our application.
    + StatefulSet Resource to run 1 replica of our database.
    + Service Resource to expose the application port. (NodePort)
    + Service Resource to expose the database port. (ClusterIP)
+ Make sure your application is reachable.
## DELIVERABLES 📦
+ Github project link (the project should be public)
+ Short demo video posted on Slack
    + show the kubernetes manifests
    + explain the app architecture
    + show load testing run
+ Load testing reports in text files on the repo, inside the dir "load_test_reports/load_test_{milestone number}"


## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Kubernetes for dummies|[Kubernetes Intro Video](https://www.youtube.com/watch?v=4ht22ReBjno&t=4s)
|Kubernetes for beginnners|[Kubernetes Fundamentals](https://medium.com/the-programmer/kubernetes-fundamentals-for-absolute-beginners-architecture-components-1f7cda8ea536)
|Kubernetes intro book|[Kubernetes Patterns](https://www.redhat.com/cms/managed-files/cm-oreilly-kubernetes-patterns-ebook-f19824-201910-en.pdf)
