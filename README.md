 # 📘 Active-Directory-Home-Lab
Windows Server 2022 Active Directory lab built in Hyper-V.

## 🧭 Lab Environment
* Hypervisor: Hyper-V Manager
* Domain Controller: Windows Server 2022 (TO-DC-01)
* Client Machine: Windows 10 (WS-01),
  * Initially named John Doe's Computer -> Changed to TO-FIN-01 -> WS-01 to reflect an appropriate general name
* Domain Name: demo.lab
* Network: Isolated virtual network

## 📚 Learning & Implementation Phases
### Phase 1: Fundamentals (Completed)

Before building the lab, I studied core Active Directory concepts:
* Active Directory structure (Domains, Trees, Forests)
* Domain Controllers
* Organizational Units (OUs)
* Users and Groups
* DNS in Active Directory environments
* Group Policy Objects (GPOs)
* Authentication concepts (Kerberos workflow)

**Key Understanding:**
User logs into a system → Workstation contacts Domain Controller → AD authenticates user → Group Policies are applied.

### Phase 2: Lab Environment Setup (Completed)
* Installed virtualization platform
* Created virtual machines:
* Windows Server 2022 (Domain Controller)
* Windows 10 (Client Workstation)
* Configured isolated virtual network

![screenshot of static IP configuration](/screenshots/phase-2-lab-environment-setup/static_IP.png)

### Phase 3: Active Directory Domain Creation (Completed)
* Installed Active Directory Domain Services (AD DS)
* Promoted server to Domain Controller
* Configured DNS integration
* Created domain: demo.lab

**Skills Practiced:**
* Forest and domain creation
* DNS configuration for AD
* Server role installation

### Phase 4: Domain Join (Completed)
* Configured Windows 10 client
* Joined workstation to domain demo.lab
* Verified authentication and DNS resolution

**Outcome:**
Successfully logged into the client using domain credentials.

### Phase 5: User & Group Administration (Completed / In Progress)
Using Active Directory Users and Computers (ADUC):

Organizational Units Created:
* Finance
* Sales
* IT (Planned)
* HR (Planned)

Users
* User Accounts Created:
* Maria Rodriguez
* Marcus Johnson

Security Groups:
* IT_Admins
* HR_Users
* Finance_Users

**Tasks Practiced:**
* Creating and managing users
* Disabling user accounts
* Unlocking accounts
* Password resets
* Group membership management

**Skills Demonstrated:**
* Identity lifecycle management
* Basic help desk user administration
* Organizational structuring using OUs and groups

### Phase 6: Group Policy (In Progress)

Currently working on implementing Group Policy Objects (GPOs).

Planned Configurations:
* Password policy enforcement
* Desktop restrictions
* Control Panel restrictions
* Command Prompt restrictions
* Login banner message
* Drive mapping policies

Skills Being Developed:
* GPO creation and linking
* Policy enforcement and inheritance
* Testing policy application
* Troubleshooting Group Policy behavior

  
## 🔜 Upcoming Phases

### Phase 7: Shared Folders & Permissions
* NTFS vs Share permissions
* Department-based access control
* Network share simulation

### Phase 8: DNS & DHCP
* DNS record management (A, CNAME)
* DHCP scope configuration
* IP assignment and reservations

### Phase 9: Troubleshooting Practice
* Login issues
*  Domain join failures
* Group Policy issues
* Network/DNS diagnostics

### Phase 10: PowerShell for Active Directory
* User creation with PowerShell
* Account management automation
* AD querying and reporting
* Phase 11: Help Desk Simulation
* Simulated IT tickets
* Password reset scenarios
* Access request workflows
* Onboarding/offboarding processes

**🧠 Key Skills Gained So Far**
* Active Directory administration
* Windows Server 2022 management
* Domain and DNS configuration
* User and group management
* Organizational Unit design
* Basic troubleshooting in domain environments

**📌 Project Goal**

This lab is designed to bridge the gap between theory and real-world IT support work by simulating enterprise Active Directory environments and common Help Desk scenarios.
