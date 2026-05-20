---
title: "NATS JetStream Deduplication for LinuxForHealth Blockchain Smart Contract Messaging"
url: "https://nats.io/blog/nats-jetstream-deduplication-for-lfh/"
date: "Mon, 19 Jul 2021 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
Deduplication of messages is a key NATS JetStream feature needed by the LinuxForHealth open source project to implement blockchain smart contract messaging. Messaging from a smart contract allows the contract to notify NATS subscribers of key contract-based decisions. This is especially helpful for blockchain client applications that may not utilize a full blockchain node and can enable message-driven smart contract workflows.
