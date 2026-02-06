# Secure Cloud VM Access (Azure)

## 📌 Project Overview
This project demonstrates how to create a secure Azure Virtual Machine and control access using Virtual Network (VNet) and Network Security Group (NSG) rules.  
It also includes troubleshooting by simulating access failure and fixing it.

## 🧰 Tools & Technologies
- Microsoft Azure
- Virtual Machine (Windows/Linux)
- Virtual Network (VNet)
- Subnet
- Network Security Group (NSG)
- RDP

## 🧱 Architecture
Client → Public IP → NSG → Network Interface → VM

## 🚀 Project Implementation

### 1️⃣ Create Azure VM
- Created a resource group
- Deployed a VM with public IP
- Verified VM running status

### 2️⃣ Configure VNet & Subnet
- Reviewed auto-created VNet
- Verified IP address range and subnet

### 3️⃣ Configure NSG Rules
- Created inbound rule to allow RDP (3389)
- Tested access after rule creation

### 4️⃣ Test Secure Access
- Successfully connected to VM using RDP
- Verified access is restricted based on rules

### 5️⃣ Failure Simulation & Fix
- Removed NSG inbound rule
- Verified RDP access failure
- Troubleshooted and re-added rule
- Access restored successfully

## 🔍 Key Learnings
- Azure networking basics
- Secure access management
- NSG rule priorities
- Real-world cloud troubleshooting

## 📷 Screenshots
Screenshots are available in the `screenshots/` folder.

## 📌 Conclusion
This project helps understand real-time cloud support scenarios involving VM access issues and network security.
# Secure-Cloud-VM-Access
Azure project demonstrating secure VM access using VNet and NSG rules
