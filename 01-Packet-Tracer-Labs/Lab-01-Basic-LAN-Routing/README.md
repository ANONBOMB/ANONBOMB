# Lab 01 - Basic LAN Routing

## Overview

This Cisco Packet Tracer lab demonstrates communication between two separate IPv4 LANs through a Cisco router.

## Topology

- 1 x Cisco 1941 Router
- 2 x Cisco 2960 Switches
- 4 x PCs
- 2 x IPv4 LANs

## Network Addressing

### LAN 1
- Network: 192.168.10.0/24
- Router Gateway: 192.168.10.1
- PC0: 192.168.10.10
- PC1: 192.168.10.20

### LAN 2
- Network: 192.168.20.0/24
- Router Gateway: 192.168.20.1
- PC2: 192.168.20.10
- PC3: 192.168.20.20

## Router Configuration

- GigabitEthernet0/0: 192.168.10.1/24
- GigabitEthernet0/1: 192.168.20.1/24
- Both interfaces enabled with `no shutdown`

## Testing

Connectivity was verified using ICMP ping tests.

Devices successfully communicated within their own LAN and across the router between the `192.168.10.0/24` and `192.168.20.0/24` networks.

## Skills Demonstrated

- Cisco Packet Tracer
- IPv4 addressing
- Subnet configuration
- Default gateways
- Cisco IOS CLI
- Router interface configuration
- Ethernet switching
- ICMP connectivity testing
- Basic network troubleshooting

## Author

**ANONBOMB**