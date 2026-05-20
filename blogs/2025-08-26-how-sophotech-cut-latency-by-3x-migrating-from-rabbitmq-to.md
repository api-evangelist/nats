---
title: "How Sophotech Cut Latency by 3x Migrating from RabbitMQ to NATS"
url: "https://nats.io/blog/sophotech-rabbitmq-to-nats/"
date: "Tue, 26 Aug 2025 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
After replacing RabbitMQ with NATS, Sophotech saw major improvements in performance and simplicity — here are their takeaways: High-level overview Sophotech migrated their ~50-service cluster from RabbitMQ to NATS. The change cut p99 latency from ~150 ms to ~40 ms, reduced ops overhead from several hours a week to under one, and eliminated queue lag during bursts (minutes -> seconds). Simpler subject-based routing also removed the need for complex RabbitMQ topology, making the system easier to operate and scale.
