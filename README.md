# Internet Networking CA-1

## Overview
This project presents the **network infrastructure** for a **ten-floor office building** at Zixel Infotech Ltd., ensuring efficient communication, scalability, and fault tolerance. The network is designed using a hybrid topology approach, a **structured IP addressing scheme**, and a **dynamic routing strategy** for inter-floor communication.

## Network Topology
The office network follows a **hybrid topology model** to optimize performance, reliability, and fault tolerance:
- **Floors 1-7:** Star topology, where six computers per floor connect to a central switch for easy management.
- **Floors 8-10:** Ring topology, ensuring smooth data flow and redundancy.
- **Router Connectivity:** All routers are connected using a **bus topology** for seamless inter-floor communication.

## IP Addressing Scheme
- **Class A Public IPv4 Addressing** is used following a **classful addressing scheme**.
- Each floor is assigned a **unique subnet** to ensure proper network segmentation.
- **Router-to-Router Communication:** Uses Class A public IPv4 addresses to maintain a consistent routing framework.

## Routing Strategy
- **Dynamic Routing** is implemented to facilitate efficient inter-floor communication.
- **Routing Protocol:** OSPF (Open Shortest Path First) is used to optimize routing decisions dynamically.
- **Network Devices Used:** Routers, switches, and access points are placed strategically for seamless connectivity.

## Connectivity Testing
- Successful **ping tests** were conducted between all floors to verify inter-LAN communication.
- The tests confirm that packets reach their destinations without loss, ensuring **network efficiency and reliability**.

## Project Files
- **Network Diagram:** A visual representation of the network topology.
- **Configuration Scripts:** Router and switch configurations for dynamic routing (if applicable).

## Future Enhancements
- Implementing **VLAN segmentation** for additional security and traffic management.
- Introducing **load balancing and failover strategies** to enhance network resilience.
- Expanding to support **wireless connectivity** for additional device access.

## Contributors
- **Vibhor Choudhary** – Network Architecture & Design
