# LDO Regulator Design and Layout using UMC 180nm CMOS

## Overview

Designed and implemented a Low-Dropout (LDO) voltage regulator using UMC 180nm CMOS technology.

## Specifications

- **Technology:** UMC 180nm CMOS
- **Supply Voltage (VDD):** 1.8 V
- **Output Voltage (VOUT):** 1.6 V
- **Load Current:** 0–1 A
- **Load Capacitance:** 4.7 µF
- **Reference Voltage:** ~1.2 V
- **Dropout Voltage:** <300 mV
- **Temperature Range:** -40°C to 125°C

## LDO Architecture

The LDO consists of:

- Bandgap Reference
- Error Amplifier
- Pass Transistor
- Feedback Network

## Design Flow

1. Circuit Design
2. Schematic Simulation
3. Transistor-Level Optimization
4. Layout Design
5. DRC Verification
6. LVS Verification
7. Parasitic Extraction (PEX)
8. Post-Layout Simulation

## Tools

- Cadence Virtuoso
- Cadence Spectre
- Siemens Calibre
- UMC 180nm CMOS PDK

## Schematic

![LDO Schematic](images/ldo-schematic.png)

## Simulation Results

### Transient Response

![Transient Response](results/transient-response.png)

### Load Regulation

![Load Regulation](results/load-regulation.png)

### Line Regulation

![Line Regulation](results/line-regulation.png)

### PSRR

![PSRR](results/psrr.png)

### Stability

![Stability](results/stability.png)

## Layout

![LDO Layout](images/ldo-layout.png)

## Physical Verification

### DRC

![DRC Results](results/drc-results.png)

### LVS

![LVS Results](results/lvs-results.png)

## Post-Layout Simulation

![Post-Layout Simulation](results/post-layout-simulation.png)

## Key Features

- Low-dropout operation
- 0–1 A load-current range
- 1.6 V regulated output
- -40°C to 125°C operating temperature range
- Full-custom transistor-level design
- Custom layout implementation
- DRC and LVS verification
- Parasitic extraction and post-layout simulation
