# Day 18 - VLAN Part 2

## Overview

Expanded on the previous VLAN lab by configuring VLAN trunking between switches and implementing inter-VLAN routing using the router-on-a-stick method.

## What I Practiced

- Configured access ports for multiple VLANs
- Created VLANs on multiple switches
- Configured and verified 802.1Q trunk links
- Restricted trunk links to required VLANs
- Configured an unused native VLAN
- Configured router subinterfaces using router-on-a-stick
- Assigned gateway addresses to each VLAN
- Verified end-to-end connectivity between VLANs

## Notes

This lab introduced router-on-a-stick, allowing a single physical router interface to route traffic between multiple VLANs using 802.1Q encapsulation. I also learned how VLANs must exist on switches carrying tagged traffic and how native VLANs and allowed VLAN lists affect trunk links.