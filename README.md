# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

![WhatsApp Image 2025-10-04 at 11 25 58_1a047469](https://github.com/user-attachments/assets/ef26b50f-51f7-464d-ab0e-82b24fb072f4)

![WhatsApp Image 2025-10-04 at 11 20 40_1e63b266](https://github.com/user-attachments/assets/89c92343-31e1-45ac-aa8c-05ec8b540a13)

![WhatsApp Image 2025-10-04 at 11 21 09_ab6b8e20](https://github.com/user-attachments/assets/19a7bbe4-d667-4d26-b8fd-1f5de2a99a47)

![Uploading WhatsApp Image 2025-10-04 at 11.25.02_392972cb.jpg…]()

![WhatsApp Image 2025-10-04 at 11 23 02_405f397d](https://github.com/user-attachments/assets/85e7fe7f-1f79-4b7e-9f7b-2c919dece3de)

![WhatsApp Image 2025-10-04 at 11 25 23_e7c107df](https://github.com/user-attachments/assets/a6bb9742-4d75-4093-be97-e0231ddb84f7)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
