---
title: "Java client usage on Android with Kotlin"
url: "https://nats.io/blog/kotlin-example/"
date: "Sat, 15 May 2021 00:00:00 +0000"
author: ""
feed_url: "https://nats.io/blog/index.xml"
---
Java Client Usage on Android with Kotlin Dependencies To use the official NATS.java library in Android we need to add the dependency to the build.gradle file at Module level. Please use the latest released version, which at this writing is 2.11.2 dependencies { //other dependencies implementation 'io.nats:jnats:2.11.2' } Implementation We will create a class as a manager to control our NATS client to be able to connect, disconnect, publish … This is necessary because when nats.
