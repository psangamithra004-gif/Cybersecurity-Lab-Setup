# Cybersecurity-Lab-Setup
VirtualBox NAT Network setup for a cybersecurity practice lab.
# 🔐 Cybersecurity Lab Setup

## VirtualBox NAT Network Configuration

This project documents the initial setup of a virtual cybersecurity laboratory using Oracle VirtualBox.

The purpose of this lab is to create a controlled virtual networking environment for cybersecurity learning, ethical hacking, penetration testing, and VAPT practice.

---

## 🎯 Objectives

- Configure a NAT Network in VirtualBox
- Create a private IPv4 network
- Enable DHCP for automatic IP address assignment
- Configure the network for future cybersecurity lab activities
- Document the laboratory network configuration

---

## 🛠️ Lab Environment

| Component | Configuration |
|---|---|
| Virtualization Platform | Oracle VirtualBox |
| Network Type | NAT Network |
| Network Name | `NatNetwork` |
| IPv4 Prefix | `10.0.2.0/24` |
| DHCP | Enabled |
| IPv6 | Disabled |

---

## ⚙️ NAT Network Configuration

A NAT Network named `NatNetwork` was configured in Oracle VirtualBox.

### Network Configuration

```text
Network Name : NatNetwork
IPv4 Prefix  : 10.0.2.0/24
DHCP         : Enabled
IPv6         : Disabled

