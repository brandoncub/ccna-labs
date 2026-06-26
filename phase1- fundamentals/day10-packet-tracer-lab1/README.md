# Day 2 – Basic Router Configuration

## Overview

This lab focuses on the fundamentals of configuring a Cisco router using the Cisco IOS CLI. The objective was to configure IPv4 addressing, enable router interfaces, add interface descriptions, verify connectivity, and save the running configuration.

## Skills Practiced

- Configuring IPv4 addresses on router interfaces
- Assigning interface descriptions
- Enabling interfaces with `no shutdown`
- Verifying interface status with `show ip interface brief`
- Reviewing configuration with `show running-config`
- Testing end-to-end connectivity using ICMP (`ping`)
- Saving the configuration to NVRAM

## Commands Used

```text
enable
configure terminal
interface g0/0
ip address
description
no shutdown
show ip interface brief
show running-config
write memory
ping
```

## Files Included

- **Day2.pkt** – Completed Cisco Packet Tracer lab
- **topology.png** – Screenshot of the completed network topology

## What I Learned

This lab reinforced the difference between configuring devices and verifying their operational state. It also introduced the role of ARP during initial connectivity tests, explaining why the first ping may time out before subsequent pings succeed once MAC address resolution has completed.
