# Task 5 - Network Traffic Analysis using Wireshark

## 📌 Objective
Capture and analyze live network traffic using Wireshark. Identify basic network protocols and understand how data flows across a network.

---

## 🛠 Tools Used
- **Wireshark** (Network Protocol Analyzer)
- **Browser/Terminal** (to generate traffic)

---

## 📥 Steps Followed

1. Opened Wireshark on the system.
2. Started packet capture on the active network interface.
3. Opened google website and ran `ping` command to generate traffic.
4. Stopped capture after around 1–2 minutes.
5. Applied filters to analyze protocols like `ICMP`, `DNS`, and `NTP` etc.
6. Exported the captured packets as a `.pcap` file.
7. Documented findings in this report.

---

## 🔍 Protocols Identified

| Protocol | Description             | Sample Info                     |
|----------|-------------------------|----------------------------------|
| DNS      | Domain Name Resolution  | Query for `www.google.com`       |
| ARP      | Web traffic             | GET request to `example.com`     |
| ICMP     | Transmission Control    | TCP handshake (SYN, ACK)         |

---

## 📝 Observations

- **ARP**: Observed ARP requests and replies where IP addresses were resolved to corresponding MAC addresses.
- **ICMP**: ICMP echo request and echo reply packets were generated using the `ping` command.
- **HTTP**: Captured HTTP GET requests and responses, including status codes like `200 OK` and website data.

---

## 📁 Files Included

- `task5_wiresharkResult.pcap` – The captured traffic file.
- `README.md` – This report summary.
---

## 💡 Learnings

- Understood real-time packet capturing.
- Learned filtering and identifying protocols in Wireshark.
- Gained hands-on experience with TCP/IP and DNS structure.
