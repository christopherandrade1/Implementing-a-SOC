=<h1>Implementing a SOC</h1>


<h2>Description</h2>

<br />


<h2>Languages and Utilities Used</h2>

- <b></b>

<h2>Environment Used</h2>

- <b>VMware</b>
- <b>Ubuntu</b>
- <b>Windows VM</b>

<h2>Project Overview:</h2>

Disable Defender on Windows VM: <br/>

- <a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">VMware</a>
- <a href="[https://ubuntu.com/download/desktop)">Ubuntu</a>
- <a href="https://www.microsoft.com/en-us/software-download/windows10">Windows 10</a>
<br />

Ensured connectivity with VM: <br/>

- Utilized the Command Line interface to retrieve the IPv4 address from my virtual machine using the 'ipconfig' command
- Executed a diagnostic procedure by initiating a ping operation to the IP address of a virtual machine from my local workstation, yielding a "Request timed out" response
- To address this matter, I disabled the Domain Profile, Private Profile, and Public Profile settings within the Windows Defender Firewall properties, consequently ensuring a stable network connectivity   

<p align="center"> 
<br />
<img src="https://imgur.com/p6qR24k.png" height="80%" width="80%" alt="Ensured connectivity with VM"/>
<br />
<br />
