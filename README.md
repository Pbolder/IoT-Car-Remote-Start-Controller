<h1>IoT-Car-Remote-Start-Controller</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)


<h2>Description</h2>
Engineered an IoT-enabled vehicle remote start controller for my car. The project included custom circuit design in Altium, PhotoMOS relay isolation for OEM key fob integration, embedded firmware development, and onboard power regulation.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Arduino as ISP</b>
- <b>Altium</b>
- <b>OnShape</b>

<h2>How it Works:</h2>
<img src="images/BlockchartCRSC.png" width="90%" alt="IoT car remote start controller block diagram"/>
An IoT relay module remotely powers the system, allowing embedded controller to interface with a modified OEM key fob. PhotoMOS-isolated outputs electronically trigger the lock and remote start button signals while onboard voltage regulation provides stable power to both the controller and key fob circuitry.

<h2>Design and Build Process:</h2>

<p align="center">
Altium schematic design: <br/>
<img src="images/AltiumSchematicCRSC.png" width="80%" alt="Altium schematic for IoT car remote start controller"/>
<br />
<br />
Arduino as ISP & Breadboard Prototype:  <br/>
<p align="center">
  <img src="images/ArduinoCodeCRSC.png" height="420" style="vertical-align: middle;" />
  <img src="images/BreadboardPrototypeCRSC.jpg" height="420" style="vertical-align: middle;" />
</p>
The code for the system was uploaded to an ATtiny85 microcontroller using an Arduino Uno as a programmer. Shown is the first working breadboard prototype used to test the smart remote start system and key fob integration before designing the final PCB.

<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
