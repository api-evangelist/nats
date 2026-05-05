---
title: "Client-side Partitioned Consumer Groups for JetStream"
url: "https://nats.io/blog/orbit-partitioned-consumer-groups/"
date: "Thu, 05 Jun 2025 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
Just added to Orbit.go is the new client-side implementation of a frequently requested feature: &lsquo; partitioned consumer groups &rsquo; for NATS JetStream!
This library is so named because what it implements is functionally equivalent to what Apache Kafka calls &lsquo;consumer groups&rsquo; and how they implement partitioning, although the functionality is not unique to Kafka. It is purely implemented by the clients using the library but requires new server functionalities introduced with NATS server version 2.
