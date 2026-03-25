<h1>Microsoft Sentinel SIEM Analysis</h1>

<h2>Description</h2>
In this project, I built a cloud-based SIEM lab using Microsoft Sentinel in Azure and connected it to a publicly exposed Windows virtual machine configured as a honeypot. The system attracted real-world RDP brute force attacks, allowing me to collect and analyze live security data. I used Log Analytics Workspace to investigate failed login attempts and identify attack patterns, including source IPs and frequency. Additionally, I developed a custom PowerShell script to pair attacker IP data with geolocation information and visualized it on a global map within Sentinel. This project provided hands-on experience with SIEM deployment, log analysis, and real-time threat monitoring in a simulated environment.

<h2>Languages Used</h2>

- <b>KQL

<h2>Environments Used</h2>

- <b>Windows (Windows Server 2025 Datacenter):</b>
- <b>Microsoft Azure:</b>
- <b>Log Analytics Workspace:</b>
- <b>Microsoft Sentinel:</b>
- <b>Resourc Groups:</b>
- <b>Microsoft Defender for Cloud:</b>
- <b>Virtual Machines:</b>

<h2>Lab walk-through:</h2>

<p align="center">
Create a Virtual Machine and Set Rules to Allow All Traffic: <br/>
<img width="2557" height="1252" alt="VM rules to allow all traffic" src="https://github.com/user-attachments/assets/adf6fa4d-1eac-4d67-b90c-9756f0e2c70c" />
Run Virtual Machine and Disable All Windows Firewall Settings: <br/>
<img width="1273" height="1392" alt="Windows firewall settings off vm" src="https://github.com/user-attachments/assets/06222b84-779e-4c55-a60d-9ab206bda8a1" />
Deploy a Log Analytics Workspace to Collect and Store Log Data From VM
<img width="2558" height="1248" alt="Log analytics workspace" src="https://github.com/user-attachments/assets/d8abde58-ef44-4cfe-bc8d-405451ff60b8" />








</p>
