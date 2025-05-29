# My-Cisco-Packet-Tracer-Labs

This repository contains hands-on labs created using Cisco Packet Tracer. Each lab simulates real-world networking scenarios and is documented with steps, screenshots, and configuration logic.

## Lab 1: Basic LAN Configuration
### My goal: 
To configure a simple Local Area Network (LAN) with two PCs and a switch, enabling successful ping communication between the PCs.
### Network Topology

![Packet Tracer LAN Topology ](https://github.com/user-attachments/assets/f1becf44-653e-4729-bab0-be59344f4da7)

### Device spesifications:
* **Switch:** Cisco 2960
* **PCs:** PC1, PC2
* **Cables:** Straight-through Ethernet cables
### Network configuration:

#### 1. PC1 IP Configuration:
* **IP Address:** 192.168.1.10
* **Subnet Mask:** 255.255.255.0
  
![PC 1 IP configuration](https://github.com/user-attachments/assets/291826bf-f328-4869-8777-6ca2a4051907)

#### 2. PC2 IP Configuration:
* **IP Address:** 192.168.1.11
* **Subnet Mask:** 255.255.255.0
  
![PC 2 Ip configuration](https://github.com/user-attachments/assets/32dc09e2-e7cd-4cc9-9b94-6732a634842b)

## Steps needed:
1. Open Cisco Packet Tracer.
2. Drag two PCs and a switch onto the workspace.
3. Connect PC1 and PC2 to the switch using copper straight-through cables.
4. Click on each PC > Desktop > IP Configuration:
   - PC1 IP: `192.168.1.1`, Subnet: `255.255.255.0`
   - PC2 IP: `192.168.1.2`, Subnet: `255.255.255.0`
5. Test connectivity:
   - Open the terminal on PC1 and type: `ping 192.168.1.2`
### Expected output:
- 4 successful ping replies
- Connection between both endpoints confirmed

![Successful connectivity](https://github.com/user-attachments/assets/4ce64da9-c8b4-40dd-91be-3a8b5e2e89c8)

### Thank you for reading, I hope this simplified the process to basic LAN configuration ;)





