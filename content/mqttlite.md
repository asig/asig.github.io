---
title: mqttlite
link: https://github.com/asig/mqttlite
---

`mqttlite` is a small and simple MQTT broker implementing protocol version 3.1.1. It supports QoS 0,1, and 2, but does not provide any kind of persistent storage. Messages and sessions will be lost if the server is shut down. Using it in my home automation setup, and it (as expected :-) works like a charm.