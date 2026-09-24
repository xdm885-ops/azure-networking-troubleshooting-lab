# Azure Networking & Troubleshooting Lab

## Project Overview

This project is a hands-on Azure networking and troubleshooting lab designed to practice foundational networking concepts in a Windows Server environment.

The lab focuses on IP addressing, subnetting, DNS resolution, TCP connectivity, RDP, HTTPS, traceroute, and basic network troubleshooting.

The goal of this project is to build practical networking skills that can be applied to entry-level IT Support, Help Desk, Network Support, and Junior Network Technician roles.

---

## Lab Environment

### Platform

- Microsoft Azure
- Azure Virtual Machine
- Windows Server 2025 Datacenter: Azure Edition
- Azure Virtual Network

### Server

- VM Name: `MonroeLab-tech`
- Domain: `monroetech.local`
- Private IPv4 Address: `172.16.0.4`

### Network

- Azure Virtual Network
- Network: `172.16.0.0/24`
- Subnet: `172.16.0.0/24`
- Subnet Mask: `255.255.255.0`
- Default Gateway: `172.16.0.1`

---

## Network Configuration

The `ipconfig` command was used to identify the server's network configuration.

- IPv4 Address: `172.16.0.4`
- Subnet Mask: `255.255.255.0`
- CIDR: `/24`
- Network: `172.16.0.0/24`
- Default Gateway: `172.16.0.1`


##Screenshots



<img width="868" height="251" alt="ethernet configuration" src="https://github.com/user-attachments/assets/adaa6ebb-21fa-4b13-b47d-0cff0e3bf83a" />

<img width="639" height="201" alt="test connection network lab" src="https://github.com/user-attachments/assets/aa9b8f86-7364-436f-bfd0-d60924a891e3" />
<img width="599" height="212" alt="network port" src="https://github.com/user-attachments/assets/e18372aa-747c-4917-a376-6424b750809d" />
<img width="549" height="299" alt="network lab" src="https://github.com/user-attachments/assets/0f4d0999-e8a6-4883-8523-3e76e8b8da69" />

<img width="825" height="228" alt="port 443" src="https://github.com/user-attachments/assets/027a0a1e-5fcf-487c-a752-bfff30fd7df8" />



---

## Connectivity Testing

### Local Connectivity

The server's local IPv4 address was tested using:

```powershell
ping 172.16.0.4

