# RSAT-Installer

This PowerShell script installs the Remote Server Administration Tools (RSAT) on a Windows system. RSAT enables IT administrators to manage roles and features on Windows Server from a remote computer running Windows.

## Features

- Installs various RSAT tools including:
  - Active Directory Domain Services and Lightweight Directory Services Tools
  - File Services Tools
  - Group Policy Management Tools
  - IP Address Management (IPAM) Client Tools
  - Link Layer Discovery Protocol (LLDP) Tools
  - Network Controller Tools
  - Network Load Balancing Tools
  - BitLocker Drive Encryption Administration Utilities
  - Certificate Services Tools
  - DHCP Server Tools
  - Failover Clustering Tools
  - Remote Access Management Tools
  - Remote Desktop Services Tools
  - Server Manager Tools
  - Shielded Virtual Machines Tools
  - Storage Migration Service Tools
  - Storage Replica Tools
  - System Insights Tools
  - Volume Activation Tools
  - Windows Server Update Services (WSUS) Tools

## Prerequisites

- PowerShell 5.0 or later
- Windows 10 or later with administrative privileges
- Internet connection for downloading and installing the RSAT components

## Usage

1. **Download the script file**: Save the script to your local machine.
2. **Open PowerShell with administrative privileges**: Right-click on the PowerShell icon and select "Run as administrator".
3. **Navigate to the script location**: Use the `cd` command to change the directory to where the script is located.
4. **Run the script**:
   ```powershell
   .\RSAT-Installer.ps1


## License

This project is licensed under the AGPL-3.0 License - see the LICENSE.md file for details.
