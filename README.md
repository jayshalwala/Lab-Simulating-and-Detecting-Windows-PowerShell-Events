# Lab: Simulating and Detecting Windows PowerShell Events

## 🔍 Objective
This lab demonstrates how to simulate suspicious PowerShell activity and detect it using Windows Event Viewer. The goal is to understand how attackers can be monitored through script execution logs and how SOC analysts leverage this data for detection and investigation.

---

## Lab Environment

- **Operating System:** Windows 10 Pro
- **Tools Used:**
  - PowerShell (built-in)
  - Windows Event Viewer
  - Group Policy Editor (gpedit.msc)

---

## Configuration Steps

### Enabled PowerShell Logging

Enabled PowerShell logging to capture detailed script execution data.

**Path in Group Policy Editor:**
