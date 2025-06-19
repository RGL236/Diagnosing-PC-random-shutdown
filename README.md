<h1>PC PC Diagnosis: Random Shutdown After Power On</h1>



<h2>Description</h2>
Project consists of a simple diagnose. Customer complained that his Desktop keeps turrning off after 5 seconds of turning it on. We will go through a series of steps to figure out the problem.
<br />


<h2>Tools Used</h2>

- <b>Phillips Screwdriver</b> 
- <b>ESD Anti Static Wrist Strap</b>

<h2>Operating System </h2>

- <b>Windows 10</b> (21H2)

<h2>Diagnostic Steps:</h2>


1. Visual Inspection

- </b>Checked all internal cables and components for loose connections.</b> 

- </b>Verified that all power connectors (24-pin motherboard, 8-pin CPU, GPU, etc.) were securely seated.</b> 

<p align="center">
Inspecting loose cables: <br/>
<img src="https://i.imgur.com/Op2hgzj.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
2. Tested with Minimal Components

  - </b>Disconnected all non-essential peripherals (HDDs, SSDs, GPU if the CPU has integrated graphics, in this case NO GPU).</b>

  - </b>Booted with only the motherboard, CPU, RAM, and power supply connected.</b>

- </b>Issue persisted—PC still shut off after a few seconds.</b>

3. Checked for Short Circuits

- </b>Removed the motherboard from the case and placed it on a non-conductive surface (e.g., cardboard).</b>

- </b>Booted the system outside the case to eliminate potential grounding or shorting from the chassis.</b>

- </b> Same behavior observed—system turned off shortly after powering on.</b>

<p align="center">
Inspecting motherboard: <br/>
<img src="https://i.imgur.com/e3PXThm.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  

4. Power Supply Unit (PSU) Test

- </b>Swapped with a known-good PSU.</b>

- </b> Still experienced shutdown after 5 seconds, ruling out a faulty PSU.</b>

5. Motherboard & CPU Test

- </b>Verified CPU seating and inspected for bent pins.</b>

- </b> Cleared CMOS by removing the circle battery (reset BIOS).</b>

- </b>No change in behavior—still powered off shortly after turning on.</b>

6. Power Button Test 

 - </b>Disconnected the front panel power switch header from the motherboard.</b>

- </b> Used a flathead screwdriver to briefly short the power switch pins manually on the motherboard to simulate the button press.</b>

<p align="center">
New Power Switch: <br/>
<img src="https://i.imgur.com/P0Hia3H.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Result: The PC powered on and stayed on normally.

Conclusion: Faulty Power Switch Button
The issue was traced to a bad power switch button. It was found that the switch was sticking or shorting internally, causing the motherboard to receive a continuous "power off" signal shortly after turning on.

Solution: Replaced the faulty power switch that was bought on ebay for $5.00, which resolved the issue.



.
.
.
.












