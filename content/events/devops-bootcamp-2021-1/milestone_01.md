---
title: Evolution Stage 0.1 AKA Build an app
description: Getting started with DevOps
slug: "milestone-01"
type: post
date: 2021-06-03
publishdate: 2021-06-03
weight: 10
---


## GOAL
Build a simple RESTful CRUD API for a merchant application to manage 2 resources; items and orders.

## MODELS
|Item|
|---|
|item id|
|name|
|cost|
|available quantity|

|Order|
|---|
|order id|
|item id|
|shopping cart id|
|requested quantity|
|total cost|

## ACCEPTANCE CRITERIA
+ The code should be stored on a public Github repository
+ An http client should be able to read, add, update, and delete items.
+ An http client should be able to read, add, update, and delete orders.
+ And order can only be placed if the requested quantity of the item is less than or equal the available quantity of that item.
+ Data should be persistent across server restarts.
+ There should be at least one test case for every possible operation (>= 8).

## REFERENCES
| Topic |  Resource  |
| ----- | ---------- |
|Framework Choice|[Flask](https://flask.palletsprojects.com/en/2.0.x/installation/)|
|Framework Choice|[Django](https://docs.djangoproject.com/en/3.2/intro/tutorial01/)|
|Software Methodology|[12 factors](https://12factor.net/)|
|Software Methodology|[12 factors illustrated](https://www.redhat.com/architect/12-factor-app)|