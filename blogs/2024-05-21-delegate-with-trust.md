---
title: "Delegate with trust"
url: "https://nats.io/blog/jetstream-eventual-consistency/"
date: "Tue, 21 May 2024 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
When speaking about async patterns (messaging, event sourcing, etc.) with other developers, they often seem afraid of eventual consistency. However, it is often expressed in the form of:
The frontend needs the answer directly
The business process needs to be validated with perfect data
My next page needs fresh data to display properly
With a messaging system, you have to wait for the message to be processed and the state to be updated.
