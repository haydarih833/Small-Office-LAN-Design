# Small Office LAN Design - Cisco Packet Tracer

## Project Overview
In this project, I designed a small enterprise network for a fictional company using **Cisco Packet Tracer**. The network includes VLAN segmentation for different departments to improve security and performance. I implemented **router-on-a-stick** for inter-VLAN routing, configured **DHCP** services to automate IP address assignment, and used **trunking** between switches and routers to ensure seamless communication across the network.

## Features
- **VLAN Segmentation**: The network was divided into multiple VLANs for different departments, such as Sales, HR, and IT. This improves network security and traffic management.
- **Router-on-a-Stick**: Configured a single router interface to provide inter-VLAN routing using sub-interfaces, enabling communication between VLANs.
- **DHCP Services**: Set up a **DHCP Server** on the router to automatically assign IP addresses to devices within each VLAN, simplifying network management.
- **Trunking**: Used trunking between switches and routers to carry traffic for multiple VLANs on a single connection.
- **Connectivity Verification**: Verified connectivity between devices using **ping** and **traceroute** commands, ensuring proper communication within and between VLANs.

## Network Design Diagram
![Network Diagram](path/to/your/diagram.png)  
*(Add a screenshot of your network diagram if you have one)*

## Technologies Used
- **Cisco Packet Tracer**
- **VLAN** (Virtual Local Area Network)
- **Router-on-a-Stick** (Subinterfaces for Inter-VLAN Routing)
- **DHCP** (Dynamic Host Configuration Protocol)
- **Trunking** (802.1Q)

## Steps Taken
1. **VLAN Configuration**:
    - Created VLANs for different departments (e.g., Sales, HR, IT).
    - Assigned switch ports to respective VLANs to segment the traffic.
2. **Router Configuration**:
    - Configured sub-interfaces on the router to enable inter-VLAN routing.
    - Implemented **Router-on-a-Stick** to allow routing between the VLANs.
3. **DHCP Setup**:
    - Configured the router to act as a **DHCP server**, assigning IP addresses dynamically to devices within each VLAN.
4. **Trunking Setup**:
    - Configured trunk links between switches and router using **802.1Q** for VLAN tagging, allowing multiple VLAN traffic to pass through a single connection.
5. **Verification**:
    - Tested connectivity using **ping** and **traceroute** to ensure proper inter-VLAN communication.

## Installation Instructions
1. Download the project file `.pkt` from the repository.
2. Open the file using **Cisco Packet Tracer** (version X or higher).
3. Review the network configuration and ensure all devices are properly connected.
4. Test the connectivity using the **ping** and **traceroute** commands from the devices.

## Project File
- [Small Office LAN Design.pkt](path/to/your/project.pkt)  
  *(Make sure the `.pkt` file is linked or included in the repo)*

## Conclusion
This project demonstrates the design and implementation of a small office network, focusing on VLAN segmentation, router-on-a-stick, DHCP services, and trunking. It showcases the ability to create a secure, efficient, and well-managed network for a small enterprise, which is essential for any growing business.

---

Feel free to explore the project and contribute with any feedback or suggestions!
