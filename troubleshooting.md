# Troubleshooting VM Access Issue

## ❌ Issue
Unable to connect to Azure VM using SSH/RDP.

## 🔍 Investigation Steps
- Verified VM power status → Running
- Verified public IP → Correct
- Checked Network Security Group rules

## 🧠 Root Cause
Inbound rule for RDP was missing or blocked in NSG.

## ✅ Resolution
- Added allow rule for required port
- Set correct priority
- Retested connection

## 📘 Lesson Learned
Network Security Groups play a critical role in controlling VM access.  
Always verify NSG rules when facing connectivity issues.

