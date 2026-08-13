<h1>IoT-Car-Remote-Start-Controller</h1>

 ### [YouTube Demonstration](https://youtube.com/shorts/W13j55whz2U?feature=share)


<h2>Description</h2>
Engineered an IoT-enabled vehicle remote start controller for my car. The project included custom circuit design in Altium, PhotoMOS relay isolation for OEM key fob integration, embedded firmware development, and onboard power regulation.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Arduino as ISP</b>
- <b>Altium</b>
- <b>OnShape</b>

<h2>How it Works:</h2>
<img src="images/BlockchartCRSC.png" width="80%" alt="IoT car remote start controller block diagram"/>
An IoT relay module remotely powers the system, allowing the embedded controller to interface with a modified OEM key fob. 
PhotoMOS-isolated outputs electronically trigger the lock and remote start button signals while onboard voltage regulation 
provides stable power to both the controller and key fob circuitry.

<h2>Design and Build Process:</h2>

<p align="center">
Altium Schematic: <br/>
<img src="images/AltiumSchematicCRSC.png" width="70%" alt="Altium schematic for IoT car remote start controller"/>
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
<p align="center">
Altium PCB: <br/>
<p align="center">

  <img src="images/PCBrCRSC.png" height="350" />
  <img src="images/PCBCRSC.png" height="350" />
</p>
The final PCB includes a mounted DC buck converter, ISP programming header, and regulated 3V output used to replace the original key fob battery.
<br />
<br />
<p align="center">
CAD Casing:  <br/>
 <img src="images/CADCRSC.png" height="350" />
<br />
<br />
Finished project:  <br/>
<p align="center">
  <img src="images/Final1CRSC.JPG" height="350" />
  <img src="images/Final2CRSC.JPG" height="350" />
</p>

<h1>Author</h1>

Designed and built by [Paul Bolder](https://github.com/Pbolder).
