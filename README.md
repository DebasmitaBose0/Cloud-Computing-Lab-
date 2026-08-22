# Cloud Computing Lab

## Experiment 1 — Virtual Machine Setup and Configuration

This repository contains the work completed for **Experiment 1** of the Cloud Computing Laboratory. The experiment focuses on creating, configuring, and verifying an Ubuntu Virtual Machine using **Oracle VirtualBox**.

---

## Objective

To install and configure an open-source hypervisor, create an Ubuntu Virtual Machine, configure its virtual hardware resources, verify that the VM runs successfully, and install the required build tools and Linux kernel headers.

---

## Software and Environment

- **Hypervisor:** Oracle VirtualBox
- **Guest Operating System:** Ubuntu
- **Architecture:** 64-bit
- **Virtual Machine:** Ubuntu 26.04
- **Network Mode:** NAT
- **Virtual CPU:** 3 CPUs
- **Base Memory:** 4096 MB
- **Virtual Hard Disk:** 25 GB

---

## Tasks Completed

### Task 1 — Install Oracle VirtualBox

Installed and configured **Oracle VirtualBox**, an open-source virtualization platform used to create and manage virtual machines.

### Task 2 — Create a New Virtual Machine

Created a new virtual machine in Oracle VirtualBox with the following configuration:

- VM Name: `Ubuntu 26.04`
- Operating System: Linux
- Distribution: Ubuntu
- Version: Ubuntu (64-bit)

### Task 3 — Configure the Virtual Machine

Configured the virtual hardware resources of the VM, including:

- CPU: 3 processors
- RAM: 4096 MB
- Storage: 25 GB virtual hard disk
- Network: NAT

### Task 4 — Configure VM Hardware

Verified the CPU, memory, storage, and network configuration through the Oracle VirtualBox settings.

### Task 5 — Configure Ubuntu Installation

Selected the Ubuntu ISO image and configured the required options for creating the Ubuntu virtual machine.

### Task 6 — Start the Virtual Machine

Started the Ubuntu virtual machine and proceeded with the boot process.

### Task 7 — Verify Ubuntu VM

Verified that the Ubuntu virtual machine successfully booted and the Ubuntu desktop environment was accessible.

### Task 8 — Install Required Build Tools

Opened the Ubuntu terminal and attempted to install the required build tools and Linux kernel headers using:

```bash
sudo apt update
sudo apt install -y build-essential linux-headers-$(uname -r)
```

Done by _Debasmita Bose_
