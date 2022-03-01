# A Memristor Emulator using 4 MOSFETs

## Table of Contents
1. [Introduction](#introduction)
2. [Reference Circuit](#reference-circuit)
3. [Implementation](#implementation)
4. [Schematic Netlist](#schematic-netlist)
5. [Simulation result](#simulation-result)
6. [References](#references)
7. [Acknowledgements](#acknowledgements)
8. [Author](#author)

## Introduction
A memristor is a 2 terminal device that is claimed to be the
4th fundamental circuit element along with resistor capacitor
and inductor. The memristance of a device is described by
the notation M (φ) where,
d(φ) = M d(q)
Real memristor devices devices such as the HP Labs TiO2
device are not that stable and not easily accessible. Thus
most research and application for memristive systems is done
with memsristor emulators that are built with a combination
of discrete components and integrated componets like BJT,
OpAmp and multipliers.
Two of the definite characteristics of a memristors are:
1. Pinched hysteresis
2. Frequency dependent hysteresis curve
As stated by Leon Chua himself, any element that is able to
show these 2 characteristics is a memristor. And thus through
an emulator, a 2 terminal device can be created that is capable
of showing these 2 characteristics.

## Reference Circuit
<p align="center">
	<img width="400" src="Images/MemCKT.png" alt="Reference circuit of MOS only memristor"> 
	<h5 align="center">Figure ?: Reference circuit of MOS only memristor</h5>
</p>

<p align="center">
	<img width="400" src="Images/MemWav2.png" alt="Reference waveform"> 
	<h5 align="center">Figure ?: Reference output to a sinusoidal input</h5>
</p>



## Implementation
<p align="center">
	<img width="400" src="Images/4T_Sche.png" alt="Scehamtic"> 
	<h5 align="center">Figure ?: The schematic recreated from the refrence</h5>
</p>
<p align="center">
	<img width="400" src="Images/4T_Symb.png" alt="Created symbol for the memristor"> 
	<h5 align="center">Figure ?: Symbol made from the schematic</h5>
</p>
<p align="center">
	<img width="400" src="Images/4T_Test.png" alt="Testbench created for the memristor"> 
	<h5 align="center">Figure ?: Testbench created for the memristor</h5>
</p>

## Simulation Result
<p align="center">
	<img width="400" src="Images/4T_Res.png" alt="Transient analysis of 20MHz sine wave"> 
	<h5 align="center">Figure ?: Transient analysis of 20MHz sine wave</h5>
</p>

## References
- Babacan, Yunus, Abdullah Yesil, and Fatih Gul. ”The fabrication and MOSFET-only circuit implementation of semiconductor memristor.” IEEE Transactions on Electron Devices 65.4 (2018): 1625-1632.

## Acknowledgements
- VSD Pvt. Ltd
- IIT Hyderabad
- Synopsys

## Author
Abel Joseph John
