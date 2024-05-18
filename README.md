# CreatingAndUsingAPortScanner

<h2>Description</h2>
How to create a simple port scanner to identify open ports on a computer, and then how to secure your system by closing unnecessary open ports using the Windows 11 firewall.
<br />


<h2>Utilities Used</h2>

- <b>Python</b> 
- <b>Windows 11 Firewall</b>
- <b>Socket: Used to create and manage network connections</b>
- <b>concurrent.futures-ThreadPoolExecutor: provides a high-level interface for asynchronously executing callables using threads</b>

<h2>Program walk-through:</h2>

<p align="center">
Importing Libraries. socket: This library provides low-level networking interface.
concurrent.futures: This library is used for executing tasks asynchronously using threads. : <br/> 
<img src="https://i.imgur.com/IxWjjJ2.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
Defining the Target IP and Port Range: <br/> 
<img src="https://i.imgur.com/2hu26xY.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
Defining the scan_port Function: <br/> 
<img src="https://i.imgur.com/KBRAc3f.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
Main Execution Block: <br/> 
<img src="https://i.imgur.com/sLnExMN.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
This script efficiently scans a range of ports on a specified IP address using multithreading to speed up the process. It provides a list of open ports, which can be useful for network security assessments and troubleshooting.: <br/> 
<img src="https://i.imgur.com/c3RIcyb.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
Now I'll just go though and close, then open a random port to further test the port scanner. And to do that I'll head into my firewall settings: <br/> 
<img src="https://i.imgur.com/z9usZAa.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
Then I'll go ahead and block port 21, 22, and 23: <br/> 
<img src="https://i.imgur.com/AKTK8Q5.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />

<p align="center">
And just like that, the ports have been blocked: <br/> 
<img src="https://i.imgur.com/L0rYnJF.png" height="80%" width="80%" alt="Port Scanner and Usage"/>
<br />
<br />


