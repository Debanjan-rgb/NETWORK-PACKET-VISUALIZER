# NETWORK-PACKET-VISUALIZER

A Python-based tool to capture live network packets and visualize:
- Protocol distribution (TCP, UDP, ICMP, etc.)
- Top source IP addresses
- Packet size trends
- Destination port usage (optional)

> ⚠️ **Note:** Run the script with Administrator/root privileges to capture packets using Scapy.

---

## 🛠️ Features

- Real-time packet sniffing with `scapy`
- Visualizations using `matplotlib`
- Data analytics with `pandas`
- Optional: Destination port scanning from TCP/UDP packets

---

## 📸 Screenshots

> Protocol distribution
 ![image](https://github.com/user-attachments/assets/b511edb8-6c93-45d2-8212-f3783a60df54)
> Top 5 source IPs
![image](https://github.com/user-attachments/assets/7bc129e5-c1f4-4cad-be74-8f43c90b2c2d)
  
> Packet length histogram
![image](https://github.com/user-attachments/assets/8a51686c-f40f-42c6-b1e1-a2cd679277a2)

> Top destination ports
![image](https://github.com/user-attachments/assets/cbb7e7a6-bf86-4636-8368-3735c57e69b8)
  


## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/network-packet-visualizer.git
cd network-packet-visualizer
