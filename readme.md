# Splunk Universal Forwarder Lab

This project demonstrates a full end-to-end configuration of a **Splunk Universal Forwarder on Ubuntu** sending logs to a **Splunk Enterprise indexer running on Windows**.  
It replicates real SOC workflows and shows practical SIEM ingestion, troubleshooting, and log verification.

---

## 🔧 Technologies Used
- **Ubuntu Linux (VirtualBox VM)**
- **Windows Splunk Enterprise 10.x**
- **Splunk Universal Forwarder 10.x**
- **TCP Port 9997 ingestion**
- **CLI tools (bash)**
- **Netstat, systemctl, Splunk CLI**
- **VirtualBox Shared Folders**

---

## 🧰 What I Configured

### ✔ Installed and initialized Splunk Universal Forwarder  
Located at:  
`/opt/splunkforwarder/bin`

Commands used:
```bash
sudo ./splunk start
sudo ./splunk status
