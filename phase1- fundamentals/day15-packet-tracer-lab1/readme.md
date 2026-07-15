# Day 15 - VLSM Network Design Lab

## Overview

This lab focused on Variable Length Subnet Masking (VLSM) by designing an IP addressing scheme for a small company network.
The completed network consisted of four LANs connected by two routers with a point-to-point connection between them.


## Network Requirements

Network Address:

192.168.5.0/24

LAN Requirements:

- LAN1 - 45 hosts
- LAN2 - 64 hosts
- LAN3 - 14 hosts
- LAN4 - 9 hosts
- Point-to-point Router Link

Requirements:

- Design appropriate VLSM subnets
- Assign the first usable IP address to each PC
- Assign the last usable IP address to each router interface
- Configure interfaces
- Configure static routes between routers
- Verify end-to-end connectivity


## Skills Practiced

- Variable Length Subnet Masking (VLSM)
- IPv4 subnet planning
- Determining subnet sizes from host requirements
- Calculating network addresses
- Calculating broadcast addresses
- Determining usable host ranges
- Interface IP configuration
- Static routing
- End-to-end connectivity verification
- Cisco IOS CLI navigation


## What I Learned

This lab helped reinforce subnetting based on business requirements rather than assigning equal-sized networks.

I also became more comfortable with:

- Reading subnet boundaries
- Recognizing network addresses versus usable host addresses
- Understanding why Cisco IOS rejects network and broadcast addresses during interface configuration
- Allocating address space efficiently using VLSM
- Building routing between multiple LANs


