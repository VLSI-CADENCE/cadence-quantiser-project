# CMOS Quantiser – Cadence Virtuoso

This repository contains the design and simulation of a **CMOS quantiser**
implemented using **Cadence Virtuoso**. The quantiser converts an analog
signal into a 1-bit digital output and is a key block of a
**Sigma–Delta Modulator**.

## Tool Used
- Cadence Virtuoso (Analog Design Environment)

## Library Name
- quantiser

## Cells Included
- **quantiser** : CMOS quantiser schematic and symbol
- **quantiser_tb** : Quantiser testbench

## Simulations
- Transient analysis
- Input: Analog (sinusoidal / ramp)
- Output: 1-bit digital waveform

## Quantiser Schematic
CMOS quantiser schematic designed using Cadence Virtuoso.

![Quantiser Schematic](images/quantiser_schematic.png)

## Quantiser Symbol
Symbol view of the quantiser used for system-level integration.

![Quantiser Symbol](images/quantizer_symbol.png)

## Optimised Quantiser Symbol
Optimised symbol representation of the quantiser.

![Optimised Quantiser Symbol](images/optimised_quantiser_symbol.png)

## Reference Circuit
Reference circuit used for designing and validating the quantiser architecture.

![Reference Circuit](Reference circuit/Quantiser_Reference.jpeg)

## Project Team
- Likhith Gowda H R
- Dhruthi Sridhar
- Adith Soragu
