<h1>Failed RDP to IP Geolocation Information</h1>

<h2>Description</h2>
In this lab,The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>ipgeolocation.io</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Program walk-through:</h2>

<p align="center">
Set up Virtual Machine: <br/>
<img src="https://imgur.com/iPpid6E.png" height="80%" width="80%" alt="Honeypot"/>
<br />
<br />
Attacks coming in; Custom logs being output with geodata: <br/>
<img src="https://imgur.com/5dsnECI.png" height="80%" width="80%" alt="Honeypotr"/>
<br />
<br />
World map of incoming attacks after 24 hours (built custom logs including geodata): <br/>
<img src="https://imgur.com/RPe9kUq.png" height="80%" width="80%" alt="Honeypot"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
