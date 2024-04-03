# Standard VM Provisioning Procedure

## Purpose
This document outlines the standard process for creating and configuring a new virtual machine (VM) within our infrastructure.

## Prerequisites
- Access to a virtualization platform (e.g., VMware, Hyper-V, cloud provider)
- Approved VM request with specifications (OS, resources, purpose)

## Steps

### VM Creation
1. Select appropriate base image / OS template
2. Allocate CPU, memory, and storage resources according to the request
3. Configure network settings (IP address, subnet mask, gateway)
4. Name the VM descriptively (e.g., webserver01-prod)

### Operating System Installation (if not using a template)
1. Mount OS installation media (ISO image)
2. Follow operating system installation wizard
3. Apply appropriate security updates and patches

### Base Configuration
1. Set hostname
2. Join domain / configure directory services (if applicable)
3. Install essential tools (monitoring agents, remote access software, etc.)
4. Harden the system according to security policies

### Application Installation and Configuration
1. Install the required application software packages
2. Configure application settings (database connections, ports, etc.)
3. Perform application-specific security configurations

### Testing
1. Verify network connectivity
2. Test application functionality
3. Conduct performance and security tests as needed

### Documentation
1. Update configuration management database (CMDB)
2. Document any IP addresses, passwords, etc. securely
3. Add instructions for access or usage in the relevant knowledge base
