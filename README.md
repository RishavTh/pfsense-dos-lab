# 🔒 DoS Detection & Mitigation Using pfSense Firewall (VirtualBox Lab)

## 🧪 Project Overview

This project simulates a **Denial-of-Service (DoS) attack detection and mitigation** setup using **pfSense Firewall** in a **virtual environment**. The goal is to demonstrate how pfSense can be used to secure a network against malicious traffic from external sources by simulating a real-world perimeter defense scenario.

## 🖥️ Lab Environment

| Role         | OS / Tool            | IP Address          | Notes                       |
|--------------|----------------------|----------------------|-----------------------------|
| Firewall     | pfSense Firewall     | WAN: 192.168.0.x     | Acts as gateway & filter    |
|              |                      | LAN: 192.168.1.1     |                             |
| Victim       | Ubuntu Desktop       | 192.168.1.100        | Target of the DoS attack    |
| Attacker     | Kali Linux           | 192.168.1.200        | Launches hping3 attack      |
| Hypervisor   | Oracle VirtualBox    |                      | Virtual lab environment     |


## 🧰 Tools Used

- **pfSense** – FreeBSD-based open-source firewall
- **Kali Linux** – Penetration testing distro (used for hping3)
- **Ubuntu Desktop** – Target/victim system
- **hping3** – Network packet generation tool (DoS simulation)
- **Wireshark** – Packet capture and analysis
- **Oracle VirtualBox** – Virtualization platform

## 🔐 Objectives

- Configure a **firewall environment** with WAN and LAN zones using pfSense.
- Simulate a **DoS attack** using `hping3` from Kali to Ubuntu.
- Capture and analyze packets using **Wireshark**.
- Create and test **firewall rules** to detect and mitigate the attack.
- Gain hands-on experience in **perimeter defense and network security**.

## 📚 Key Learnings

- Importance of **firewall rule ordering** and specificity
- How to isolate and identify malicious traffic
- Hands-on configuration of **pfSense DHCP, NAT, and rule sets**
- Understanding virtualized network layouts for security testing
