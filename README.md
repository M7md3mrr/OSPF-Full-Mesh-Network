# OSPF Full Mesh Network Lab

## Overview
This project demonstrates the implementation of OSPF dynamic routing using Cisco Packet Tracer.

## Topology
The network consists of:
- 4 Routers
- 4 LANs
- Full Mesh Router Connectivity
- OSPF Area 0

## Network Addressing

| LAN | Network |
|------|---------|
| LAN 1 | 192.168.1.0/24 |
| LAN 2 | 192.168.2.0/24 |
| LAN 3 | 192.168.3.0/24 |
| LAN 4 | 192.168.4.0/24 |

## Verification

### Network Topology
![Topology](screenshots/topology.png)

### OSPF Neighbors
![OSPF Neighbors](screenshots/ospf-neighbor.png)

### Routing Table
![Routing Table](screenshots/show-ip-route.png)

### Connectivity Test
![Ping Test](screenshots/ping-test.png)

## Commands Used

```bash
show ip route
show ip ospf neighbor
show ip protocols
show ip interface brief
```

## Author

Mohamed Amr
