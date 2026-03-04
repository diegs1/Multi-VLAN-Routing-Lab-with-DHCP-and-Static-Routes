Implementation of a small enterprise-style campus network using VLAN segmentation, inter-VLAN routing, DHCP services, and static routing.

Key Concepts
- Inter-VLAN Routing
- DHCP Configuration (HQ MLS) - Created separate DHCP pools per VLAN to automatically assign IP addresses and default gateways.
- IP Static Routing - Configured manual ip route entries to define paths to external or remote networks.

Result
- All PCs successfully receive IP addresses via DHCP.
- Devices within and across VLANs can communicate.
- Static routes correctly forward traffic to remote networks.
- End-to-end connectivity verified using ping and routing table checks.

What I Learned
- How DHCP pools must align correctly with VLAN gateways and subnet design.
- How static routes determine packet forwarding beyond directly connected networks.
- How Layer 2 trunking enables multiple VLANs to traverse between switches.
- How to systematically verify routing, addressing, and end-to-end connectivity.
- The importance of proper IP planning before implementing services.

<img width="1568" height="651" alt="routing-dhcp-topology" src="https://github.com/user-attachments/assets/d3d444f7-3313-42cf-9d45-db0ef753b6cd" />
