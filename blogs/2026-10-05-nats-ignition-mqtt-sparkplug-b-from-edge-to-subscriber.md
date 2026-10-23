---
title: "NATS + Ignition MQTT: Sparkplug B from Edge to Subscriber"
url: "https://nats.io/blog/nats-ignition-mqtt-sparkplug/"
date: "2026-10-05"
feed_url: "https://nats.io/blog/index.xml"
---
I’ve been building out an IIoT pipeline using NATS as the backbone for Sparkplug B telemetry from Ignition SCADA. This post covers the Docker setup: standalone NATS with JetStream and MQTT, Ignition Transmission publishing from the edge, and a Python subscriber decoding Sparkplug B on the other end. No leaf nodes, no hub.
