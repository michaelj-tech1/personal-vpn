# Personal VPN Infrastructure

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue.svg)](https://github.com/michaelj-tech1/personal-vpn)

## Overview
**Personal VPN Infrastructure** is a fully deployed and managed VPN service using OpenVPN, designed to support multiple users with secure encrypted traffic. By leveraging 20 global servers, this project ensures that all incoming and outgoing traffic is routed securely while enforcing strict firewall rules and integrating Fail2Ban for intrusion prevention.

## Features
- **Global Deployment:**  
  Deployed OpenVPN servers across 20 global locations to provide reliable and secure VPN access.
- **Automated Provisioning:**  
  Initially configured servers manually, then implemented Ansible for automated provisioning, updates, and maintenance across all nodes.
- **Secure Traffic Routing:**  
  Routes all incoming and outgoing traffic securely with enforced firewall rules.
- **Intrusion Prevention:**  
  Integrated Fail2Ban to prevent unauthorized access and protect against potential intrusions.
- **Custom User Interface:**  
  Built with Python and PySide6, the GUI enables real-time connection control and server selection.

## Prerequisites
- **Python 3.7** or later  
- **Internet Connection** for VPN access and remote server management  
- **Ansible** for automated server provisioning and maintenance  
- **OpenVPN** installed on each server  
- **Fail2Ban** configured for intrusion prevention  
- **Python with PySide6** for the custom user interface

## Installation

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/michaelj-tech1/personal-vpn.git
   cd personal-vpn
