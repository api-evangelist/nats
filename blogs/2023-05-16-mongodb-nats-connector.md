---
title: "MongoDB NATS Connector"
url: "https://nats.io/blog/mongodb-nats-connector/"
date: "Tue, 16 May 2023 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
Data Synchronization Between Microservices With microservice architectures becoming the standard nowadays, it is a common need to extract data from your database to synchronize other downstream services. Consider a social network where you have a service that stores new posts in a MongoDB collection. You may want to notify other services when a post is created, perhaps so that you can save it on Redis for fast retrieval, or add it to Elastic for full text search queries.
