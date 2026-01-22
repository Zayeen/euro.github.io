---
layout: post
title: "Self-Hosting a Voice Assistant"
date: 2026-01-02
categories: [IoT]
tags: [Privacy, AI]
---

## Self-Hosting a Voice Assistant

Rhasspy and Piper...

### The Context
As smart homes evolve, the complexity of managing devices increases.


Future improvements will include migrating to the new V2 API which offers better type safety.

Data privacy is paramount. All logs are stored locally on an SSD and rotated every 7 days.

The cost per unit is slightly higher, but the reliability justifies the investment for critical infrastructure like leak sensors.

Security is another major factor. By isolating these devices on a separate VLAN, we ensure that compromised firmware cannot pivot to the main network.

Security is another major factor. By isolating these devices on a separate VLAN, we ensure that compromised firmware cannot pivot to the main network.

Integration with Home Assistant was seamless via MQTT. The auto-discovery feature saved us hours of manual configuration.

Firmware updates are handled OTA (Over The Air), which is convenient but introduces a potential attack vector if not secured properly.

The cost per unit is slightly higher, but the reliability justifies the investment for critical infrastructure like leak sensors.

The cost per unit is slightly higher, but the reliability justifies the investment for critical infrastructure like leak sensors.

We ran a stress test with 50 concurrent connections. The CPU usage on the controller never exceeded 15%, proving the efficiency of the code.

Integration with Home Assistant was seamless via MQTT. The auto-discovery feature saved us hours of manual configuration.

Security is another major factor. By isolating these devices on a separate VLAN, we ensure that compromised firmware cannot pivot to the main network.

We ran a stress test with 50 concurrent connections. The CPU usage on the controller never exceeded 15%, proving the efficiency of the code.

The cost per unit is slightly higher, but the reliability justifies the investment for critical infrastructure like leak sensors.

The power consumption analysis revealed interesting data. The sleep current was approximately 15uA, which aligns with the datasheet specifications.

Data privacy is paramount. All logs are stored locally on an SSD and rotated every 7 days.


### The Technical Details
In this experiment, we set out to solve a specific problem in the lab.

1.  **Analysis:** We started by analyzing the traffic patterns and power consumption.
2.  **Implementation:** Using open-source tools, we built a solution that runs locally.
3.  **Testing:** We stress-tested the setup for 7 days.

> "Security is not a product, but a process." - Bruce Schneier


Firmware updates are handled OTA (Over The Air), which is convenient but introduces a potential attack vector if not secured properly.

Data privacy is paramount. All logs are stored locally on an SSD and rotated every 7 days.

The power consumption analysis revealed interesting data. The sleep current was approximately 15uA, which aligns with the datasheet specifications.

Integration with Home Assistant was seamless via MQTT. The auto-discovery feature saved us hours of manual configuration.

The community support for this project is incredible. There are hundreds of plugins available that extend the functionality beyond the core features.

However, range can be an issue. We had to add two router nodes to cover the basement and the garage effectively.


### Final Thoughts
This setup has improved stability significantly. If you are building a similar system, I highly recommend focusing on local control first.
