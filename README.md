
**Packet Sniffer using Scapy**
A simple packet sniffer built with Python and Scapy to analyze network traffic.
It captures and analyses network packets in real time.
the tool wil extract and display useful information such as source and destination IP addresses, protocol used( TCP, UDP, ICMP),Port numbers, packet payload data

## *Features*
- Captures network packets in real-time.
- Filters packets based on protocols (TCP, UDP, ICMP, etc.).****
- Displays packet details such as source, destination, and protocol type.

## *Requirements*
- Python 3.11+
- Scapy
- *Windows Users*: Install [Npcap](https://nmap.org/npcap/) for Layer 2 sniffing.

 install Npcap before running the script.

RuntimeError: Sniffing and sending packets is not available at layer 2: WinPcap is not installed.

- Install Npcap and restart your system.
- Run the script as an administrator.

