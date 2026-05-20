---
title: "Infinite message deduplication in JetStream"
url: "https://nats.io/blog/new-per-subject-discard-policy/"
date: "Mon, 14 Nov 2022 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
One feature, released in the v2.9.0 NATS server , that flew under the radar was the new DiscardNewPerSubject option on a stream. This blog post will describe this new feature as well as give a practical example of how it can be used to provide exactly-once message publication quality of service (QoS) through infinite deduplication that goes beyond the existing time-based deduplication feature of JetStream as well as many other streaming systems, such as Kafka.
