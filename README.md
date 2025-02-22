# NSA POOL – YOU SHALL NOT PASS

## Context

This project, completed as part of the **DevOps NSA 501** module at **EPITECH**, involves setting up a network infrastructure consisting of **four virtual machines (VMs)**. These machines are connected through a network configured with strict security rules, aiming to manage and filter network traffic effectively.

### Virtual Machines:

- **VM1 (Gateway)**: Router with NAT, DHCP, and packet filtering.
- **VM2 (Web Server)**: Hosting web services with Nginx, PHP, and MySQL.
- **VM3 (Administration)**: Management workstation.
- **VM4 (Employee)**: User workstation with restricted access.

## Tools and Technologies

### Virtualization:

- **VirtualBox**: For creating and managing VMs.
- **OpenBSD 7.6**: Operating system for the Gateway.
- **FreeBSD**: OS for the web server.
- **Debian 12**: OS for administrative and employee workstations.

### Software and Services:

- **Nginx**: Web server to host pages and applications.
- **PHP 7.4**: Programming language for dynamic applications.
- **MySQL**: Database management system.
- **SSH**: Secure connection between machines.

### Network Configurations:

- **DHCP**: Dynamic IP address allocation for subnets.
- **Packet Filter (PF)**: Network filtering rules for security.
- **NAT**: Internal address masking for outgoing connections.

## Steps Completed

1. **VM Creation and Configuration**:
   - Allocation of resources (RAM, CPU, storage).
   - Installation of operating systems.
   - Configuration of network interfaces (NAT, internal networks).

2. **Network Configuration (VM1)**:
   - Setting up **DHCP** for subnets.
   - Applying **PF** rules to control incoming and outgoing traffic.
   - Enabling port forwarding for **SSH** access.

3. **Service Deployment (VM2)**:
   - Installation of **Nginx**, **PHP**, and **MySQL**.
   - Configuring services to meet user requirements.

4. **Testing and Validation**:
   - Verifying connections between all VMs.
   - Testing Internet access (Ping, traceroute).
   - Validating security rules and network functionality.

## How to Launch the Project

1. **Prerequisites**:
   - Install VirtualBox.
   - Download ISO files for OpenBSD, FreeBSD, and Debian.

2. **Installation**:
   - Follow the steps outlined in the documentation to create and configure the VMs.
   - Ensure the network and filtering rules are properly set up.

3. **Verification**:
   - Conduct connectivity and service access tests to validate the infrastructure.
