# Cybersecurity-Lab-Setup
VirtualBox NAT Network setup for a cybersecurity practice lab.
This project documents the initial setup of a virtual cybersecurity laboratory using Oracle VirtualBox.

The purpose of this lab is to create a controlled virtual networking environment for cybersecurity learning, ethical hacking, penetration testing, and VAPT practice.


## 🎯 Objectives

- Configure a NAT Network in VirtualBox
- Create a private IPv4 network
- Enable DHCP for automatic IP assignment
- Configure the network for future cybersecurity lab machines
- Document the laboratory setup
## 🛠️ Lab Environment

| Component | Configuration |
|---|---|
| Virtualization Platform | Oracle VirtualBox |
| Network Type | NAT Network |
| Network Name | `NatNetwork` |
| IPv4 Prefix | `10.0.2.0/24` |
| DHCP | Enabled |
| IPv6 | Disabled | NAT Network Configuration

A NAT Network named `NatNetwork` was configured in Oracle VirtualBox.

### Configuration

```text
Network Name : NatNetwork
IPv4 Prefix  : 10.0.2.0/24
DHCP         : Enabled
IPv6         : DisabledIPv4 Network

The configured IPv4 network is:

10.0.2.0/24

The corresponding subnet mask is:

255.255.255.0

DHCP is enabled to allow virtual machines connected to the NAT Network to obtain IP addresses automatically.NAT Network Configuration

The configuration shows:

IPv4 Prefix: 10.0.2.0/24
DHCP: Enabled
IPv6: Disabled
🪜 Configuration Steps
Step 1: Open VirtualBox

Open Oracle VirtualBox on the host system.

Step 2: Open Network Manager

Open the VirtualBox Network Manager to configure the virtual network.NatNetwork
Step 4: Configure IPv4

Set the IPv4 prefix to:

10.0.2.0/24
Step 5: Enable DHCP

Enable DHCP to allow connected virtual machines to automatically receive IPv4 addresses.

Step 6: Configure IPv6

IPv6 is disabled for the current laboratory configuration.

🔎 Network Information
Setting	Value
Network Address	10.0.2.0
CIDR	/24
Subnet Mask	255.255.255.0
DHCP	Enabled
IPv6	Disabled
🛡️ Purpose of the Lab

This virtual environment is being prepared for cybersecurity learning and authorized security-testing activities.

The laboratory can later be used for:

Network reconnaissance
Port scanning
Service enumeration
Vulnerability assessment
Web application security testing
Packet analysis
Penetration testing
VAPT practice

All security testing should be performed only against systems that are owned by the tester or where explicit authorization has been provided.

🚀 Future Activities

The following activities can be added as the laboratory is developed:

 Connect Kali Linux to NatNetwork
 Verify IP address assignment
 Test connectivity between virtual machines
 Add an intentionally vulnerable target machine
 Perform Nmap scanning
 Perform service enumeration
 Practice vulnerability assessment
 Document testing results
📚 Learning Outcomes

Through this setup, I learned:

How to create a NAT Network in VirtualBox
How to configure an IPv4 network
How CIDR notation works
The purpose of DHCP in a virtual environment
How virtual networking can be used to build a cybersecurity laboratory
The importance of documenting technical configurations
⚠️ Ethical Use

This laboratory is intended for educational and authorized cybersecurity activities only.

Security testing must not be performed against systems without proper authorization.

👤 Author

Sangamithra P

Cybersecurity Learner | Offensive Security & VAPT

📌 Project Status

Status: Initial NAT Network Configuration Completed

Current Network Setup
VirtualBox
    │
    └── NAT Network
          │
          ├── Name: NatNetwork
          ├── IPv4: 10.0.2.0/24
          ├── DHCP: Enabled
          └── IPv6: Disabled
📂 Repository Structure
Cybersecurity-Lab-Setup/
│
├── README.md
│
└── screenshots/
    ├── nat-network-manager.png
    └── nat-network-configuration.png

### Important

Before you paste this, make sure your screenshot filenames are exactly:

```text
nat-network-manager.png
nat-network-configuration.png

and your repository has:

Cybersecurity-Lab-Setup
│
├── README.md
└── screenshots
    ├── nat-network-manager.png
    └── nat-network-configuration.png

Step 3: Create a NAT Network

Create a new NAT Network with the following name:
