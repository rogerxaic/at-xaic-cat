---
title: "Homelab setup"
date: "2021-05-26"
lastmod: "2021-05-28"
description: "My first attempt at creating a homelab."
tags:
  - Network
  - Homelab
categories: 
  - Tech
image: "thomas-jensen-ISG-rUel0Uw-unsplash.jpg"
license: Licensed under CC BY-NC-SA 4.0 - Header image by Thomas Jensen on Unsplash.
---

Back in 2014 I bought my first Raspberry Pi. At first it was only meant for tinkering. Homelab-ing, though, is like opening a bag of chips: once you start, you won't be able to stop 😅.

However Raspberry Pies aren't meant for production – I often found the RPi had destroyed the SD card, not to mention that back then they were _slow_. So I kept my RPi for tinkering and ordered an Ubuntu droplet on DigitalOcean ([use this link to get $100 in credit](https://m.do.co/c/2cd92a75e89f) 🤑) for my production side projects and self-hosted apps.

---
## WIP

Needs?:

* Storage
* Compute power
* Doesn't break as often as rpi
* Others?

## My first production-grade server

HPE Microserver Gen8 + 2 x 4Tb HDDs on a RAID1 setup.

Best thing of my homelab is that it was not planned & has evolved ==> lots of learning

---

Used to run a mail server + updated the Linux kernel ==> the mail server stopped running

    Lessons learnt
      * Test on a staging env before updating prod
      * Don't run your own mail server
