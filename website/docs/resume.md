# Résumé

Download a PDF of my résumé [here](./things/resume.pdf).
<div>The following gives more detailed descriptions of things enumerated on my résumé.</div>

### Education

<p>
<div>Tufts University Class of 2020</div>
<div>B.S. in Computer Engineering</div>
<div>GPA: 3.91</div>
</p>

<p>
<div>Santa Cruz High School Class of 2016</div>
<div>Valedictorian</div>
</p>

### Current Work

I am currently working at [Tulip Interfaces](https://tulip.co) on the IoTH (IoT/Hardware) team. I interned there over the summer, and am continuing my work into the school year as a part-time engineer. Some of the things I am working/have worked on:

<ul>

<li> <strong>Installing Tulip OS on x86 devices.</strong> This involves getting Tulip's Yocto layer to boot on devices such as the Dell 3002 and Up Squared Board. </li>

<li> <strong>ADC calibration board PCB design, fabrication, testing, and code integration into Tulip's gateway.</strong> Altium was used for the PCB design, and the boards were fabricated without any parts soldered on. I hand-soldered all components onto the boards, which included stable voltage sources (using zener diodes) and Wien Bridge oscillators. The device received power from Tulip's gateway and output voltages, which I then wrote a utility for to calculate ADC calibration coefficients. </li>

<li> <strong> Wrote eMMC flasher scripts for Nanopi-R1 boards. </strong> Using a reference Nanopi image, I added a partition and inserted a Tulip image into the reference image. Once this expanded reference image was burned onto an SD card, I wrote a utility that burned the SD card to the Nanopi's on-board eMMC so that after the SD card was removed, Tulip OS would boot from the eMMC. </li>

<li> <strong> Hardware and code debug for Gizmo: a version of the <a href="https://github.com/formatc1702/Micro-Word-Clock">MicroWorld clock.</a></strong> Initially used an Arduino as an ISP to load bootloader and .ino code onto the clock's ATMega chip, then switched over to using command line utilities and AVR MKII programmer. </li>

</ul>

### Skills

Computer/software 
~~~
- Linux
- Kernel development
- Bash scripting
- C/C++
- MATLAB
- Git/GitHub
- Yocto Project
- ARM, MIPS
- Python
- HTML/CSS
- Javascript
~~~

Electrical engineering/hardware
~~~
- PCB design (Altium)
- Cadence
- VHDL
- SPICE
- Soldering
- Circuit theory/design
~~~