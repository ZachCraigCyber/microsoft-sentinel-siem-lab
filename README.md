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
Create Resource Group to Organize all Components such as the VM, Network Settings, and Sentinel Workspace: <br/>
<img width="2559" height="1251" alt="resource group" src="https://github.com/user-attachments/assets/5a2636cc-2555-43e8-8aab-374ad4894124" />
Create a Virtual Machine and Set Rules to Allow All Traffic: <br/>
<img width="2557" height="1252" alt="VM rules to allow all traffic" src="https://github.com/user-attachments/assets/adf6fa4d-1eac-4d67-b90c-9756f0e2c70c" />
Run Virtual Machine and Disable All Windows Firewall Settings: <br/>
<img width="1273" height="1392" alt="Windows firewall settings off vm" src="https://github.com/user-attachments/assets/06222b84-779e-4c55-a60d-9ab206bda8a1" />
Deploy a Log Analytics Workspace to Collect and Store Log Data From VM: <br/>
<img width="2558" height="1248" alt="Log analytics workspace" src="https://github.com/user-attachments/assets/d8abde58-ef44-4cfe-bc8d-405451ff60b8" />
Deploy Mirosoft Defender for Cloud to Monitor the Environment for Security Risks and Misconfigurations: <br/>
<img width="2554" height="1256" alt="Microsoft Defender for Cloud" src="https://github.com/user-attachments/assets/74e4eb18-7fd5-498f-9a3a-95881e479400" />
KQL Query to Search for Failed Login Attempts: <br/>
<img width="2559" height="1342" alt="Log Analytics workspace KQL query" src="https://github.com/user-attachments/assets/d8b0f09f-a22e-4dac-ac2f-ed9cab2ad246" />
Deploy Microsoft Sentinel with a Watchlist to Analyze Logs and Store GeoIP Data: <br/>
<img width="2559" height="1250" alt="Microsoft Sentinel Watchlist" src="https://github.com/user-attachments/assets/f1c2907f-ba23-4270-a749-db6458b122e8" />
<img width="2553" height="1251" alt="watchlost geoip query" src="https://github.com/user-attachments/assets/c2139dda-d3ae-4bdc-9352-dcfff2f3c41b" />
<img width="2558" height="1254" alt="kql watclist on one ip" src="https://github.com/user-attachments/assets/33b01e0d-bcc1-457b-851b-7dacae4deada" />
Windows Virtual Machine Attack Map: </br/>
<img width="2558" height="1249" alt="Windows Vm attack map" src="https://github.com/user-attachments/assets/4d0ad4b5-4f3b-4a1e-a91a-ec321e7a9aea" />







</p>
