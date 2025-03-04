Internet Networking CA-1
Overview
This project presents a comprehensive network design for a ten-floor office building, ensuring efficient communication, scalability, and fault tolerance. The network follows a hybrid topology approach, utilizes dynamic/static routing for inter-floor communication, and implements a structured IP addressing scheme to support seamless connectivity.
Network Topology
The office network integrates multiple topologies to optimize performance, reliability, and fault tolerance:
•	Floors 1-7: Star topology, where six computers per floor connect to a central switch for simplified network management and scalability.
•	Floors 8-10: Ring topology, ensuring redundancy and smooth data flow with minimal transmission delays.
•	Router Connectivity: All routers are connected through a hierarchical structure, ensuring seamless inter-floor communication and efficient routing.
IP Addressing Scheme
The network follows a structured IP allocation strategy:
•	All Floors: Assigned Class A public IPv4 addresses to enable unique and scalable addressing.
•	Subnetting is applied to ensure efficient IP allocation while minimizing wastage.
•	Router-to-Router Communication: Uses Class A public IPv4 addresses to maintain a structured routing framework.
Routing Strategy
•	A dynamic routing approach (OSPF) is implemented to allow automatic route updates, scalability, and adaptability.
•	If static routing is used, predefined static routes ensure predictable and controlled data flow between floors.
Connectivity Testing
•	Successful ping tests confirm that all LANs across the ten floors communicate seamlessly.
•	The network design ensures packet transmission without losses, validating efficiency, reliability, and fault tolerance.
Project Files
•	Network Diagram: A visual representation of the complete topology.
•	Configuration Scripts: Router and switch configurations for static or dynamic routing (to be added if required).
Future Enhancements
•	VLAN segmentation for enhanced security and traffic management.
•	Load balancing and failover mechanisms for improved network resilience.
•	Wireless connectivity integration for greater device accessibility.
Contributors
•	Vibhor Choudhary – Network Architecture & Design

