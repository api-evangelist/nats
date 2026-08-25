---
title: "Building a Wallet Event Backbone with NATS JetStream: Lessons from BroSettlement's Staging Tests"
url: "https://nats.io/blog/brosettlement-building-a-wallet-event-backbone-with-nats-jetstream/"
date: "2026-08-17"
feed_url: "https://nats.io/blog/index.xml"
---
I am Vadym Rozov, founder of BroLabel , where we are building BroSettlement : API-first, noncustodial MPC wallet, ledger, and settlement infrastructure for fintech, iGaming, and crypto-native platforms. A wallet transaction is not one synchronous request. It moves through policy checks, MPC signing, blockchain broadcast, confirmation, ledger posting, and client notification, and any of those stages may be delayed or fail independently.
