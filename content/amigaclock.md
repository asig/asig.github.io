---
title: AmigaClock
link: https://github.com/asig/amigaclock
---

An analog desk clock styled after the classic AmigaOS 1.2 Workbench, running on the Guition/Sunton ESP32-4848S040 (ESP32-S3 with a 480x480 touch display).

The clock gets its time over Bluetooth Low Energy from a companion Android app, which can also hand over Wi-Fi credentials so the clock keeps itself in sync via NTP. The repository contains the ESP-IDF firmware, the Android app, and the BLE protocol specification.
