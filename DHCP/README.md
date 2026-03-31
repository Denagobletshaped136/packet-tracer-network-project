# DHCP Configuration for 20 PCs using Cisco Packet Tracer 🌐

## 📌 Project Overview

This project demonstrates the configuration of Dynamic Host Configuration Protocol (DHCP) in Cisco Packet Tracer to automatically assign IP addresses to 20 PCs in a network.

---

## 🧰 Tools Used

* Cisco Packet Tracer

---

## 🏗️ Network Setup

* 1 Router (DHCP Server)
* 1 Switch
* 20 PCs
* Ethernet (copper straight-through) cables

---

## ⚙️ Configuration Details

### 🔹 Router Configuration (DHCP Server)

```bash
enable
configure terminal

interface gig0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
exit

ip dhcp pool LAN
network 192.168.1.0 255.255.255.0
default-router 192.168.1.1
dns-server 8.8.8.8
exit

end
write memory
```

---

### 🔹 Excluding IP Addresses (Optional but Recommended)

```bash
ip dhcp excluded-address 192.168.1.1 192.168.1.10
```

👉 Prevents router and reserved IPs from being assigned

---

## 💻 PC Configuration

For all 20 PCs:

* Go to **Desktop → IP Configuration**
* Select **DHCP**

👉 Each PC will automatically receive:

* IP Address
* Subnet Mask
* Default Gateway

---

## 🧪 Testing Connectivity

Use Command Prompt in any PC:

```bash
ping 192.168.1.1
```

👉 If replies are received → DHCP is working successfully

---

## 📊 Expected Result

* All 20 PCs receive unique IP addresses automatically
* Network communication is successful

---

## 🎯 Learning Outcomes

* Understanding DHCP concept
* Automatic IP allocation
* Router as DHCP server
* Network scalability

---

## 📂 Files Included

* `dhcp-topology.pkt` → Packet Tracer file
* Screenshots of DHCP configuration

---

## 👩‍💻 Author

Divya Sree
