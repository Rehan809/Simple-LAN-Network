Here's a simple example of a README file for a basic LAN network setup with two PCs and one switch:

---

# Simple LAN Network with 2 PCs and 1 Switch

## Overview

This project demonstrates a simple Local Area Network (LAN) configuration consisting of:
- **2 PCs**
- **1 Switch**

The network is designed to showcase basic networking concepts such as IP addressing, connectivity, and the role of a switch in managing network traffic.

## Network Topology

```
[PC1] --- [Switch] --- [PC2]
```

### Components:
1. **PC1**: A computer connected to the switch.
2. **PC2**: A second computer connected to the switch.
3. **Switch**: A network switch to connect the two PCs and facilitate communication between them.

## Objective

- Set up a simple network where **PC1** and **PC2** can communicate with each other.
- Assign static IP addresses to both PCs.
- Use the switch to manage the communication between both devices.

## Configuration

### Step 1: Assign IP Addresses
- **PC1**: Assign a static IP address of `192.168.30.1`, subnet mask `255.255.255.0`.
- **PC2**: Assign a static IP address of `192.168.30.2`, subnet mask `255.255.255.0`.

### Step 2: Connect Devices
- Connect **PC1** to the switch via Ethernet cable.
- Connect **PC2** to the switch via Ethernet cable.

### Step 3: Test Connectivity
- From **PC1**, ping **PC2** using the command:
  ```bash
  ping 192.168.1.20
  ```
- If everything is set up correctly, you should receive a response from **PC2**.

## Packet Tracer Configuration

This project is designed in Cisco Packet Tracer. The `.pkt` file contains the full configuration of the devices, including the switch and both PCs. You can open the Packet Tracer file to visualize the network and interact with the devices.

## Files Included

- **LAN_Network.pkt**: Packet Tracer file containing the network configuration.
- **Network_Configuration.txt**: A text file outlining the configuration details, including IP addresses and test results.

## Requirements

- Cisco Packet Tracer (for viewing and interacting with the `.pkt` file).
- Basic knowledge of networking concepts (IP addressing, subnetting, pinging).

## How to Use

1. Open the `LAN_Network.pkt` file in Cisco Packet Tracer.
2. Review the configuration of both PCs and the switch.
3. Test the connectivity by pinging between the PCs.
4. Refer to the `Network_Configuration.txt` file for detailed instructions and setup information.

## Conclusion

This simple LAN network with two PCs and a switch demonstrates basic networking concepts like IP addressing, subnetting, and the role of switches in a network. The setup is ideal for beginners to understand how devices communicate within a local network.

