---
title: "Exploring NATS as a backend for k3s"
url: "https://nats.io/blog/exploring-nats-as-a-backend-for-k3s/"
date: "Tue, 09 May 2023 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
k3s is a lightweight Kubernetes distribution suitable for IoT and edge computing environments. One component k3s leverages is KINE , which is a shim enabling the replacement of etcd with alternate storage backends originally targeting relational databases. In April 2022, the v0.9.0 release of KINE introduced native support for NATS as a backend.
