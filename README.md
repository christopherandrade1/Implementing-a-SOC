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

Installed and setup WMware, Ubuntu, Windows VM: <br/>

- <a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">VMware</a>
- <a href="https://ubuntu.com/download/desktop)">Ubuntu</a>
- <a href="https://www.microsoft.com/en-us/software-download/windows10">Windows 10</a>
<br />

Disable Defender on Windows VM: <br/>

- Permanently disabled Microsoft Defender so it doesn't interfere with further shady steps planned for this project
- Disabled Tamper Protection 

<p align="center"> 
<br />
<img src="https://imgur.com/o6gSKAN.png" height="80%" width="80%" alt="Disable Defender on Windows VM"/>
<br />
<br />

- Permanently Disable Defender via Group Policy Editor

<p align="center"> 
<br />
<img src="https://imgur.com/lrQ22vl.png" height="80%" width="80%" alt="Disable Defender on Windows VM"/>
<br />
<br />

- Permanently Disable Defender via Registry

<p align="center"> 
<br />
<img src="https://imgur.com/4IZKSZz.png" height="80%" width="80%" alt="Disable Defender on Windows VM"/>
<br />
<br />

- Boot into Safe Mode to disable all Defender services
- Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Sense
- Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\WdBoot
- Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\WinDefend
- Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\WdNisDrv
- Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\WdNisSvc
- Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\WdFilter

<p align="center"> 
<br />
<img src="https://imgur.com/5VnA9cw.png" height="80%" width="80%" alt="Disable Defender on Windows VM"/>
<br />
<br /> 

Install Sysmon in Windows VM: <br/>

- 
<br />
