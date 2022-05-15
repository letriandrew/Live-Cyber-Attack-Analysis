<h1>Live-Cyber-Attack-Analysis</h1>

<h2>Description</h2>
<br />The Powershell script in this repository is used to parse out Windows Event Log information for failed RDP attacks and uses a third party API (ipgeolocation.io) to collect geographic information about the attackers location.
<br />

<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />

<h2>Tools and Utilities Used</h2>
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 
