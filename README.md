# 🚀 Active Directory and IIS Lab Project

## 📋 Project Overview
This project demonstrates the end-to-end deployment of a secure enterprise network environment using Windows Server. The primary objective is to establish centralized identity management and host a scalable web service.

## 🎯 Objectives
- 🖥️ **Deploy and configure Windows Server roles**, including Active Directory Domain Services and IIS.
- 📂 **Structure identity management** using Organizational Units and security groups.
- 🔐 **Implement access control lists** to secure shared resources.
- 🌐 **Verify web server accessibility** and functionality.

## 🛠️ Tools Used
- **Windows Server**: Core operating system and domain controller.
- **PowerShell**: Automation and management interface.
- **IIS**: Web server hosting.

## 🏗️ Implementation Steps

### Phase 1: Infrastructure Setup
- Installed and promoted Windows Server to a Domain Controller.
- Enabled necessary server roles for directory and web services.

### Phase 2: Active Directory Management
- Created a dedicated Organizational Unit (OU) named **'ProjetPro'**.
- Provisioned a test user **'TestUser'** within the structured OU.
- Created a Global Security Group **'ProjetTeam'** and assigned the user as a member.

### Phase 3: Access Control and Permissions
- Established a shared directory **'C:\ProjetPartage'**.
- Configured explicit ACL permissions granting Modify access to the user and group.

### Phase 4: Web Server Verification
- Verified IIS installation and default web page availability.
- Tested network connectivity and server responsiveness.

## 🏁 Conclusion
This project successfully establishes a foundational enterprise infrastructure, demonstrating competence in user lifecycle management, resource security, and web hosting configuration.
