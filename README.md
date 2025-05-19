# Packet Sniffing & Spoofing Lab (SEED Labs)

This project demonstrates how to sniff and spoof network packets using Scapy and raw socket programming. It includes ICMP, TCP, and Telnet-based sniffing, as well as crafting spoofed packets and injecting them into the network.

## 🔍 Objective
- Learn packet-level network inspection and manipulation
- Use Scapy to sniff and spoof ICMP/TCP packets
- Craft raw C-based sniffers and spoofers using `pcap` and `raw sockets`
- Sniff Telnet credentials from TCP payloads
- Explore subnet-specific packet filters and spoofed replies

## 🧰 Tools Used
- Scapy (Python)
- C with libpcap
- Wireshark
- Docker (SEED Ubuntu VM)
- Telnet & Netcat

## 📌 Key Tasks Completed
- **ICMP Sniffing & Spoofing:** Captured ping requests and sent spoofed replies
- **TCP Packet Capture:** Captured TCP traffic and filtered by port ranges
- **Telnet Password Sniffing:** Intercepted credentials from TCP payloads
- **Subnet Filtered Packets:** Sent/monitored packets specific to subnet ranges
- **C-based Sniffer:** Built raw C packet sniffer to capture headers and payload
- **ICMP Spoofing with Raw Sockets:** Injected echo replies for fake hosts

## 🛡️ Key Observations
- Root privileges are required to use raw sockets and sniff interfaces
- Promiscuous mode is needed to see traffic not directly addressed to host
- Multiple replies observed when spoofing a real destination (e.g., 8.8.8.8)

## 🖼️ Screenshots
Optionally include terminal logs or Wireshark captures of spoofed and sniffed traffic.

## 📁 Files
- `packet-sniffing-report.pdf` – Full writeup with code, tests, and attack validation

## 📄 Author
**Aparnaa Mahalaxmi Arulljothi**  
Student ID: A20560995

---

## 🔗 References
- [SEED Labs - Packet Sniffing and Spoofing](https://seedsecuritylabs.org/Labs_20.04/Networking/Sniffing_Spoofing/)
- [Scapy Docs](https://scapy.readthedocs.io/en/latest/)
