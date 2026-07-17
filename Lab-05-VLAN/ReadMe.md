# Lab 05 - VLAN Configuration

## Overview

This lab demonstrates VLAN configuration in Cisco Packet Tracer. A single Layer 2 switch is used to divide the network into four separate Virtual Local Area Networks (VLANs), allowing devices in different departments to communicate only with members of the same VLAN.

## Network Topology

![Topology](screenshots/01-Topology/Lab-05-VLAN-Configuration.png)

## Devices

| Device | Quantity |
|---------|---------:|
| Switch | 1 |
| PCs | 8 |
| VLANs | 4 |

## VLAN Configuration

| VLAN ID | Department | Members |
|---------:|------------|---------|
| 2 | Finance | PC1, PC2 |
| 3 | HR | PC3, PC4 |
| 4 | IT | PC5, PC6 |
| 5 | Administration | PC7, PC8 |

## Features

- VLAN Creation
- Port Assignment
- Layer 2 Network Segmentation
- Broadcast Domain Isolation
- End-to-End Connectivity within the Same VLAN

## Verification

The following tests were completed successfully:

- ✅ VLANs created successfully
- ✅ Switch ports assigned to the correct VLANs
- ✅ Successful ping between devices in the same VLAN
- ✅ Devices in different VLANs are isolated

## Files

- `Lab-05-VLAN.pkt`
- `Lab-05-VLAN-Configuration.png`
- `screenshots/`
