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

### Screenshot

_Add network configuration screenshot here._

---

## Connectivity Testing

### Local Connectivity

The server's local IPv4 address was tested using:

```powershell
ping 172.16.0.4

