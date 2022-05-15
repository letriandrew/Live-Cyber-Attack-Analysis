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
<br />
- <b>Microsoft Azure:</b> Extract RDP failed logon logs from Windows Event Viewer 
<br />
- <b>ipgeolocation.io:</b> Extract RDP failed logon logs from Windows Event Viewer 
<br />

<h2>World map of incoming attacks after roughly 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/VM30Z6x.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
