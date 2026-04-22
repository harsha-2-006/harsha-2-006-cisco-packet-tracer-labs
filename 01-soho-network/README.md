# SOHO Network Design (Cisco Packet Tracer)

## Overview

This lab demonstrates the design and implementation of a Small Office/Home Office (SOHO) network using Cisco Packet Tracer. The network supports both wired and wireless clients with automatic IP configuration using DHCP.

---

## Topology

The network consists of:

- 1 Wireless Router (HomeRouter-PT)
- 1 Cable Modem (Internet connectivity)
- 2 Switches (2960 series)
- 3 PCs (wired connections)
- 1 Laptop (wireless connection)

The router acts as the central device, providing:
- DHCP services
- Wireless access
- Connectivity to the internet via the cable modem

---

## Configuration Details

### Router Configuration
- DHCP enabled for automatic IP assignment
- Wireless network (SSID) configured
- WPA2 security enabled with passphrase
- LAN ports used to connect switches

### Switch Configuration
- Default configuration (Layer 2 switching)
- Connected to router via Ethernet ports

### End Devices
- PCs configured to obtain IP using DHCP
- Laptop connected via Wi-Fi using SSID and passphrase

---

## Network Operation

- All devices receive IP addresses from the router's DHCP server
- Wired devices communicate through switches
- Wireless device connects directly to the router
- Router acts as the default gateway for all devices

---

## Testing and Verification

The following tests were performed:

- Verified IP assignment using:
