# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## 📌 Objective
The objective of this task is to capture live network packets using Wireshark, identify basic protocols, and analyze traffic types.

---

## 🛠 Tools Used
- **Wireshark** (Version: [Your Version])
- **Npcap** (Version: [Your Version])

---

## 📂 Steps Performed

1. **Installed Wireshark** along with **Npcap** for packet capturing.
2. Opened Wireshark and selected the **active network interface** (`Wi-Fi` in my case).
3. Started packet capture and generated traffic by:
   - Browsing websites
   - Running `ping google.com` in Command Prompt
4. Captured packets for approximately **1 minute**.
5. Stopped the capture and applied display filters for specific protocols:
   - `http` – to view HTTP traffic
   - `dns` – to view DNS queries and responses
   - `tcp` – to view TCP connections
6. Saved the capture file as `task5_capture.pcap`.
7. Took screenshots of filtered packet views for documentation.

---

## 🔍 Protocols Identified

| Protocol | Description | Example Packet Observation |
|----------|-------------|-----------------------------|
| **HTTP** | Hypertext Transfer Protocol – used for web communication | Request to `example.com` with status code `200 OK` |
| **DNS** | Domain Name System – resolves domain names to IP addresses | Query for `google.com` resolved to IP `142.250.x.x` |
| **TCP** | Transmission Control Protocol – connection-oriented reliable protocol | 3-way handshake observed between client and server |

---

## 📸 Screenshots

### 1. HTTP Filter
![HTTP Packets](screenshots/http.png)

### 2. DNS Filter
![DNS Packets](screenshots/dns.png)

### 3. TCP Filter
![TCP Packets](screenshots/tcp.png)

---

## 📁 Files in Repository
- `task5_capture.pcap` – Packet capture file
- `README.md` – This report
- `screenshots/` – Folder containing all protocol screenshots

---

## 📚 Key Learning
- Learned to capture live network traffic using Wireshark.
- Understood the role of **HTTP, DNS, and TCP** in network communication.
- Practiced filtering and analyzing specific protocol traffic.
- Gained basic awareness of packet structures and network troubleshooting.

---
