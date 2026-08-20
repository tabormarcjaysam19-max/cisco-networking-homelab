# cisco-networking-homelab
Hands-on Cisco networking lab focused on VLAN configuration using Cisco Packet Tracer.


## Project Overview
This project documents my hands-on networking practice using Cisco Packet Tracer. The lab focuses on configuring and troubleshooting Cisco switches and routers through the Cisco IOS CLI while building a small multi-VLAN network.


## Network Topology
The following topology represents the network used in this lab.

![Network Topology](imagesnetwork-topology.png)


## Technologies & Tools
- Cisco Packet Tracer
- Cisco IOS CLI
- VLANs
- Ethernet Switching
- Trunking
- IP Addressing
- DHCP
- Network Troubleshooting


- ## Network Configuration
### 1. VLAN Configuration
Created and configured VLAN 10 and VLAN 20 on the switch to separate devices into different logical networks.

### 2. Access Port Configuration
Assigned switch access ports to their respective VLANs:
- Fa0/1 → VLAN 10
- Fa0/3 → VLAN 10
- Fa0/2 → VLAN 20

### 3. Trunk Configuration
Configured a switch port as a trunk link to carry traffic from multiple VLANs between network devices.

### 4. IP Addressing
Configured IP addresses, subnet masks, and default gateways for network devices and end devices.

### 5. DHCP Configuration
Configured DHCP to automatically assign IP addresses and other network information to connected end devices.

### 6. Connectivity Testing
Verified network connectivity using Cisco IOS CLI commands and ping tests. Checked VLAN assignments, trunk status, IP addressing, and device connectivity.


## Lab Tasks
### Lab 1: Basic Network Setup
- Created a network topology using Cisco Packet Tracer.
- Added and connected PCs, switches, and routers.
- Configured basic device settings using the Cisco IOS CLI.
- Assigned device names for easier identification.
- Verified physical and logical connections between network devices.

### Lab 2: VLAN Configuration
- Created VLAN 10 and VLAN 20 on the switch.
- Assigned switch access ports to the appropriate VLANs.
- Configured:
  - Fa0/1 → VLAN 10
  - Fa0/2 → VLAN 20
  - Fa0/3 → VLAN 10
- Used `show vlan brief` to verify VLAN assignments.

### Lab 3: Trunk Configuration
- Configured trunk links between network devices.
- Verified trunk status using Cisco IOS CLI commands.
- Checked VLANs allowed on trunk links.
- Troubleshot trunk configuration issues affecting VLAN connectivity.

### Lab 4: IP Addressing
- Assigned IP addresses and subnet masks to network devices and end devices.
- Configured default gateways for end devices.
- Verified IP addressing using Cisco IOS CLI commands.
- Tested connectivity between devices using `ping`.

### Lab 5: DHCP Configuration
- Configured DHCP on the network to automatically assign IP addresses to end devices.
- Configured DHCP network settings, including the default gateway.
- Verified that end devices successfully received IP addresses.
- Troubleshot devices that were not receiving IP addresses from DHCP.

### Lab 6: Network Connectivity Testing
- Tested connectivity between network devices using `ping`.
- Used Cisco IOS verification commands to check device and interface configurations.
- Identified connectivity issues involving VLAN assignments, trunk links, IP addressing, and default gateways.
- Corrected network configuration issues and retested connectivity.


## Testing & Troubleshooting
Connectivity was tested using ping and Cisco IOS verification commands.
### Troubleshooting Example
**Issue:** End device was not receiving an IP address.

**Investigation:**
- Checked the device's IP configuration.
- Verified the switch port VLAN assignment.
- Checked the DHCP configuration.
- Verified connectivity between the switch and connected devices.

**Resolution:** Corrected the network configuration and verified successful IP address assignment and connectivity.


## Future Labs
- Inter-VLAN Routing
- Static Routing
- OSPF
- Access Control Lists (ACLs)
- Port Security
- Network Security
- VPN Configuration
- Advanced Network Troubleshooting
