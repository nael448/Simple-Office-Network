# Simple-Office-Network
SIMPLE OFFICE NETWORK WITH 2  DEPARTMENT(HR AND IT)

Simple Office Network Topology Work
work Overview

This Work involves the design and implementation of a simple local area network for an office environment using Cisco Packet Tracer. The network is built as a single flat network using static IP configurations to provide stable and reliable connectivity across all office workstations without complex segmentation.
Network Architecture and Design

The topology relies on a straightforward, centralized network model to ensure easy maintenance and direct communication:

    Core Routing: A single router serves as the central gateway to handle external traffic and connect the local office network to outside services.

    Switching Layer: An unsegmented switch handles local network traffic, connecting all office computers together in a single broadcast domain.

    Static IP Management: Rather than using dynamic addressing, the network implements a manual, structured IPv4 static addressing scheme. Every workstation, printer, and network interface is assigned a permanent IP address to ensure predictable host mapping and easy tracking.

Key Technical Features

    Flat Network Topology: Designed without VLANs, allowing all devices in the office to communicate directly with one another across the local switch without needing inter-VLAN routing.

    Static Addressing: Every endpoint is manually configured with a dedicated IP address, subnet mask, and default gateway to prevent address conflicts and eliminate dependency on a DHCP server.

    Direct Connectivity: Devices share the same network space, facilitating seamless resource sharing (such as network printers and local file sharing) across the entire office.

File Contents

    simple office network.pkt: The complete, executable Cisco Packet Tracer simulation file containing the configured router, switch, and statically addressed end devices.

How to Run the Simulation

    Download and install Cisco Packet Tracer on your computer.

    Clone or download this repository to access the simulation file.

    Open simple office network.pkt within Packet Tracer.

    Click on any computer, navigate to the Desktop tab, and open IP Configuration to view its static IP setup.

    Use the command prompt on any workstation to ping another device's static IP to verify successful network connectivity.
