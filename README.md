# Enterprise-LAN-Design
3-tier Hierarchical LAN Design with Core, Distribution and Access layer.

This project demonstrates the design and implementation of a scalable and secure enterprise LAN using a hierarchical network model. The topology is built to support multiple departments, redundancy, dynamic routing, and controlled inter-VLAN communication.
The network follows a three-tier hierarchical architecture consisting of Core, Distribution, and Access layers. This design improves scalability, fault tolerance, and ease of management.

The core layer consists of two core switches configured with Layer 3 switching, OSPF dynamic routing, EtherChannel using LACP, and loopback interfaces for stable routing.

The distribution layer includes multiple switch pairs responsible for inter-VLAN routing, HSRP-based gateway redundancy, ACL enforcement, and DHCP relay configuration.

The access layer connects end devices and assigns VLANs based on department. Trunk links are used between access and distribution layers.

OSPF is used throughout the network for dynamic routing. HSRP and EtherChannel provide redundancy and high availability.

Security is enforced using ACLs and secure SSH access.
This project showcases an enterprise-grade LAN design using industry best practices.

