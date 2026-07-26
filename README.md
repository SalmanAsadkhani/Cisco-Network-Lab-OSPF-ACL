# Network Design using Cisco Packet Tracer

## Project Overview

This project demonstrates the design and implementation of an enterprise network
with multiple VLANs, dynamic routing, DHCP services, ACL security policies.

The topology was designed based on a real-world enterprise network scenario.

---

## Technologies Used

- Cisco Packet Tracer
- VLAN
- DHCP
- IPv4 Addressing
- Static Routing
- OSPF Routing Protocol
- ACL (Access Control List)
- Network Troubleshooting

---

## Network Design

The network consists of:

- Two different sites connected through WAN links
- Multiple VLANs for user segmentation
- Central DHCP server
- Web Server in remote network
- Dynamic routing using OSPF

---

## Implemented Features

### VLAN Configuration

Created separate VLANs:

- VLAN 10
- VLAN 20

Each VLAN has its own IP subnet and DHCP configuration.

---

### DHCP Service

Configured DHCP services to automatically assign IPv4 addresses
to clients inside VLAN 10 and VLAN 20.

---

### Routing

Implemented:

- Static Routing
- OSPF Dynamic Routing

OSPF was configured to provide automatic route exchange between routers.

---

### Security (ACL)

Configured ACL rules to:

- Allow HTTPS access to Web Server
- Block unauthorized traffic
- Control communication between networks

---

## Testing

Performed tests:

- Ping between VLANs
- Ping between routers
- DHCP address assignment verification
- Routing table verification
- ACL functionality testing

---

## Skills Demonstrated

- Network Design
- Cisco Routing & Switching
- VLAN Implementation
- OSPF Configuration
- DHCP Management
- Basic Network Security
- Troubleshooting
