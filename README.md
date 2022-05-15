<h1>Live-Cyber-Attack-Analysis</h1>

<h2>Description</h2>
<br />The Powershell script in this repository is used to parse out Windows Event Log information for failed RDP attacks and uses a third party API (ipgeolocation.io) to collect geographic information about the attackers location.
<br />

<br />
To begin this analysis, Azure Sentinal must be set up. We will use Sentinal as a SIEM (Security Information and Event Management) to detect failed RDP Brute Force attacks. These attacks will take place on a live virtual machine connected to our SIEM to be used as a honey pot. These attempts will be observed and analyzed from around the world with the help of a custom PowerShell script to plot the attacker's Geolocation info and plot it on an Azure Sentinal Map.
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
