# Creating a Windows Virtual Machine

A hands-on lab creating a Windows 11 virtual machine using Oracle VirtualBox for
Data Security Concepts (CIT245) at T.A. Marryshow Community College.

## Overview

This lab covers the full process of setting up a Windows virtual machine from scratch:

- Downloading the official Windows 11 ISO from Microsoft
- Configuring virtual machine hardware settings in VirtualBox
- Booting the VM from the ISO to verify the installation media loads correctly

## Lab Activities

### Creating a Windows Virtual Machine
Downloaded the Windows 11 multi-edition ISO for x64 devices from
www.microsoft.com/software-download/windows11 and created a new VM in
Oracle VirtualBox with the following configuration:

| Setting | Value |
|---------|-------|
| VM Name | Win11VM |
| RAM | 4 GB (4096 MB) |
| CPU Cores | 2 |
| Disk Size | 80 GB |
| Network Mode | NAT |
| ISO File | Windows 11 multi-edition ISO for x64 devices |

After clicking Finish, the VM was launched by double-clicking Win11VM in the left
pane. The VM booted from the ISO, displayed the Windows logo, and loaded the
language selection screen confirming the installation media was attached and working
correctly.

## Key Takeaways

- Virtual machines provide an isolated sandbox environment where malware or system
  failures cannot affect the host computer
- One physical machine can run multiple VMs simultaneously, saving hardware costs
  and enabling quick setup of test environments
- Proper hardware allocation of RAM, CPU, and storage is important for the VM to
  run efficiently
- The boot order must be configured to the optical drive for the VM to start from
  the ISO installer

## Tools Used

| Tool | Purpose |
|------|---------|
| Oracle VirtualBox | Hypervisor for creating and running the virtual machine |
| Windows 11 ISO (microsoft.com) | Guest operating system installation media |

## VM Configuration

| Component | Detail |
|-----------|--------|
| Hypervisor | Oracle VirtualBox |
| Guest OS | Windows 11 (multi-edition x64) |
| Virtual Hard Disk Format | VMDK |
| Network Adapter | NAT |

## Environment

- Host OS: Windows 11
- Hypervisor: Oracle VirtualBox

## License

<strong>[&copy; 2026 Ahndre Walters](https://github.com/AhndreWalters/Creating-a-Windows-Virtual-Machine/blob/main/LICENSE) · Creating a Windows Virtual Machine · TAMCC Data Security Concepts Course · College Course Assignment</strong>
