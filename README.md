# FPU
SoC-level Physical Design RTL to GDSII Flow of a 32-bit Floating Point Unit

# 32-bit Floating Point Unit - Physical Design (RTL to GDSII)

## Overview
This project implements the physical design of a 32-bit Floating Point Unit at the SoC level using RTL to GDSII flow. The design follows an industry-relevant flow for synthesis, floorplanning, placement, CTS, routing, and physical verification.

## Tools Used
- Design Compiler
- IC Compiler II
- PrimeTime
- Calibre

## Technology Details
- **Node**: 14nm
- **Metal Layers**: 8
- **Instance Count**: ~100K

## Key Contributions
- Performed **physical synthesis** to optimize area, power, and reduce WNS.
- Designed **floorplan** including I/O port placement, macro placement, and power planning.
- Implemented **multi-voltage domains** using level shifters and reduced power consumption.
- Created **placement blockages and keep-out margins** to manage congestion.
- Achieved **69% utilization** with no congestion or density issues.
- Debugged and resolved **setup/hold violations** using PrimeTime.
- Fixed **max transition and capacitance violations** across multiple scenarios.


