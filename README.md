# VSD_ChipDesign_Workshop_Documentation
<h2>Advance Physical Design using OpenLANE Sky130</h2>
Author: Anurag Devidas Biradar
<br>
This is my summary for VSD Workshop on Chip designing using Google Skywater 130nm PDK process using <a href="https://github.com/efabless/openlane2">OpenLANE</a> tool chain flow.
<h2>Introduction to Workshop</h2>
This workshop was about giving tutorial of Advance Physical Design using Openlane SKY130.
<h3>Day_1: Inception of Open Source EDA, OpenLANE and SKY130 PDK</h3>
<h4>How to talk to computers?</h4>
<details><summary><b>Introduction to QFN-48 Package, Chip, Pads, Core, Die and IPs</b></summary>
<br>
Arduino Leonardo is a common example of electronics board. It is based on ATmega32u4 chip, and for which we are intrested about. 
<br><br>
![](Images/Arduino%20Leonardo%20Board.png)
Basic fundamental terminologies:
<br><br>
<b>Package:</b>
It is a housing in which ICs are placed. Ex: QFN48 (i.e., Quad Flat No-Lead Package with 48 leads) is one of kind of package in market.
<br><br>
<b>Wire bonds:</b>
It is an electrical interconnection between pins and chip.  
<br><br>
<b>Pads:</b>
Metal connections on IC package which provide electrical connection between chip and PCB.
<br><br>
<b>Core:</b>
It is a place where all the digital logic (such as AND gate, OR gate, etc.) is placed. 
<br><br>
<b>Die:</b>
It is small piece of semiconductor material on which IC is fabricated. Also, die contains many number of cores in it. 
<br><br>
<b>Foundry IPs:</b>
Foundry IPs (Intellectual Property) are predesigned blocks which can be directly used by customers of that foundry. It includes blocks like SRAM, ADC, DAC, PLL, etc.
<br><br>
<b>Macros:</b>
It is pieces of predesigned logic blocks which can be used without need of designing them from start. 
<br><br>


</details>
OpenLANE is an automated tool chain for RTL to GDSII flow. 
It includes various tools like Yosys, OpenSTA, OpenROAD, Magic, Netgen and other such Custom Scripts for designing and optimization.
