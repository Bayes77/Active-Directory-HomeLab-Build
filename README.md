# 🛡️ Active Directory Home Lab

## 📌 Goal
The goal of this lab is to get hands-on experience creating and setting up an Active Directory environment. I plan to build on the experience gained in this project to further develop my cybersecurity skills through practical, hands-on work.

---

## 🧰 Tools Used
- VirtualBox
- Windows Server
- Active Directory
- Windows 10

---

## ⚙️ Phase 1: Domain Controller Configuration
In this phase, I configured the Domain Controller.

**Configurations:**
- Initial setup of the Domain Controller environment


---

## 🖥️ Phase 2: Windows Server & Active Directory Setup
In this phase, I installed Windows Server and set up Active Directory on the Domain Controller.

**Steps:**
- Installed Windows Server
- Viewed the Windows Server dashboard after installation
- Renamed network adapters to:
  - `Internal`
  - `Internet`
- Assigned a static IP address
- Installed Active Directory using the **Add Roles and Features** wizard

📸 *Windows Server Dashboard*  
📸 *Network Adapter Configuration*  
📸 *Active Directory Installation*  

---

## 🌐 Phase 3: Core Services Configuration
In this phase, I:
- Promoted the Domain Controller
- Installed Remote Access Services (RAS/NAT)
- Installed the DHCP role
- Created a new DHCP scope

### 🔑 Promoting the Domain Controller
📸 *Add screenshot*

---

### 🌍 Remote Access (RAS) & NAT Setup
- Selected the Remote Access feature
- Installed the Remote Access role
- Configured NAT
- Selected the public interface

📸 *Add screenshots*

---

### 📡 DHCP Configuration
- Installed Remote Server Administration Tools
- Began DHCP scope configuration
- Configured IP address range
- Completed DHCP setup

📸 *Add screenshots*

---

### 🧑‍💻 Verification
- Confirmed CLIENT1 is listed after configuration

📸 *Add screenshot*

---

## 💻 Phase 4: Client Machine Setup
- Created the CLIENT1 virtual machine
- Verified connection to the Domain Controller

📸 *Add screenshot*

---

## 🧠 Skills Demonstrated
- Active Directory setup and configuration  
- Domain Controller promotion  
- Network configuration (Static IP, NAT)  
- DHCP scope creation and management  
- Virtualization using VirtualBox  
- Windows Server administration  

---

## 🚀 Future Improvements
- Simulate Active Directory attacks (e.g., Kerberoasting, Pass-the-Hash)  
- Integrate a SIEM (e.g., Splunk or ELK)  
- Add monitoring and detection rules  
- Expand lab with additional users and machines  

---

## 📎 Notes
This lab is part of my ongoing cybersecurity learning journey focused on building real-world, hands-on experience.

