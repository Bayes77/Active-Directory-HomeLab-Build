
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

<img width="1279" height="939" alt="Screenshot 2026-04-16 104344" src="https://github.com/user-attachments/assets/1f109b9d-ae49-4329-ad4b-2fb85830b670" />

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

<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_11_36_04" src="https://github.com/user-attachments/assets/bef0405b-99ea-4e25-956e-457ff67d50cc" />

<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_11_37_43" src="https://github.com/user-attachments/assets/064e1aef-177d-44da-8d19-500f0383ab05" />


---

## 🌐 Phase 3: Core Services Configuration
In this phase, I:
- Promoted the Domain Controller
- Installed Remote Access Services (RAS/NAT)
- Installed the DHCP role
- Created a new DHCP scope

### 🔑 Promoting the Domain Controller
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_11_40_52" src="https://github.com/user-attachments/assets/42cfce39-8898-4a90-92d9-7ec9087180e0" />


---

### 🌍 Remote Access (RAS) & NAT Setup
- Selected the Remote Access feature
- Installed the Remote Access role
- Configured NAT
- Selected the public interface
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_11_58_57" src="https://github.com/user-attachments/assets/81ac5b76-0d51-487b-9403-be458361c1e0" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_11_59_35" src="https://github.com/user-attachments/assets/76b3a3ba-fe28-469f-8a06-a0654c975d02" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_03_29" src="https://github.com/user-attachments/assets/e1df4a74-9f60-4107-9ae5-413cc127a883" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_04_04" src="https://github.com/user-attachments/assets/d9b76ca4-023c-41e9-9f1e-0ba2732ddc43" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_05_35" src="https://github.com/user-attachments/assets/2e2e0475-8867-462b-a285-df3bf853be15" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_05_55" src="https://github.com/user-attachments/assets/a5714cdd-5c29-41d6-a82b-7dc5e5085325" />







---

### 📡 DHCP Configuration
- Installed Remote Server Administration Tools
- Began DHCP scope configuration
- Configured IP address range
- Completed DHCP setup
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_08_05" src="https://github.com/user-attachments/assets/dd4a6020-119d-433f-8054-85fad0b71fc1" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_08_47" src="https://github.com/user-attachments/assets/06f8941f-6449-425c-8298-1520e9978528" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_10_06" src="https://github.com/user-attachments/assets/421930eb-d9dc-40e4-b018-eba262ef91a6" />
<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_12_14_59" src="https://github.com/user-attachments/assets/759de1eb-9b13-426b-be46-bd65f5ea378d" />



---

### 🧑‍💻 Verification
- Confirmed CLIENT1 is listed after configuration

<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_13_22_10" src="https://github.com/user-attachments/assets/4755d1df-7ef9-4f3d-af36-15621d0646f6" />


---

## 💻 Phase 4: Client Machine Setup
- Created the CLIENT1 virtual machine
- Verified connection to the Domain Controller

<img width="1810" height="1005" alt="VirtualBox_DC01_11_04_2026_13_23_49" src="https://github.com/user-attachments/assets/cf71739c-69fa-4082-8267-dd8bb7b9664c" />



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

