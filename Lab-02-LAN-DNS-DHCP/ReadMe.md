# Lab 02 - LAN, DNS, DHCP and Web Server

## Overview

This lab demonstrates a small LAN network using Cisco Packet Tracer. The topology includes a DHCP server for automatic IP address assignment, a DNS server for domain name resolution, and two web servers that can be accessed using their domain names.

## Network Topology

![Topology-DHCP](screenshots/01-Topology/Topology-DHCP.png)

## Devices

| Device | Quantity |
|---------|---------:|
| Router | 1 |
| Switch | 1 |
| Client PCs | 3 |
| DHCP Server | 1 |
| DNS Server | 1 |
| Web Servers | 2 |

## Network Configuration

### IP Addressing

- Student PC uses a **Static IP Address**.
- Client-1 and Client-2 receive their IP addresses automatically from the DHCP server.
- The DNS server and both web servers use Static IP addresses.

### DNS Configuration

The DNS server is configured to resolve the following domain names:

- `google.com`
- `iran.network.ir`

### DHCP Configuration

The DHCP server automatically assigns:

- IPv4 Address
- Subnet Mask
- Default Gateway
- DNS Server

to client devices inside the Engineering Faculty LAN.

## Features

- Static and Dynamic IPv4 Addressing
- DHCP Configuration
- DNS Configuration
- Web Server Configuration
- Automatic IP Assignment
- Domain Name Resolution
- End-to-End Connectivity

## Verification

The following tests were completed successfully:

- ✅ DHCP successfully assigned IP addresses to Client-1 and Client-2
- ✅ Ping between all devices
- ✅ DNS name resolution
- ✅ Access to `google.com`
- ✅ Access to `iran.network.ir`

## Files

- `Lab-02-LAN-DNS-WebServer-DHCP.pkt`
- `Topology-DHCP.png`
- `screenshots/`
