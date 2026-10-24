# STEP-MXO2-C FPGA Development Board

**Compact Lattice MachXO2-4000HC FPGA Learning Board with Onboard LPC11U35 Programmer**

A compact and versatile FPGA development board designed for students, makers, educators, and embedded hardware enthusiasts.

The **STEP-MXO2-C**, developed by **Nova Step Tech**, features a Lattice MachXO2-4000HC FPGA, an onboard LPC11U35 programmer, USB Type-C connectivity, and essential peripherals in a compact **52 × 18 mm DIP40-style form factor**.

It provides an accessible platform for learning digital logic, developing HDL projects, and exploring FPGA-based embedded systems.


---

## Key Features

- **Lattice MachXO2-4000HC FPGA** — LCMXO2-4000HC-4MG132
- **4,320 LUTs** for digital logic and FPGA applications
- **Onboard LPC11U35 programmer** — no separate programming adapter required for normal development
- **USB Type-C** — power, FPGA programming, and UART communication
- **36 user expansion I/Os**
- **2-digit 7-segment display**
- **2 RGB LEDs** and **8 user LEDs**
- **4 DIP switches** and **4 push buttons**
- **SPI, I2C, UART, and GPIO interfaces**
- **Compact 52 × 18 mm design**
- **Lattice Diamond support**
- **Verilog and VHDL development**

## Hardware Specifications

| Parameter | Specification |
|---|---|
| Board Model | STEP-MXO2-C |
| FPGA | Lattice LCMXO2-4000HC-4MG132 |
| FPGA Family | MachXO2 |
| Logic Resources | 4,320 LUTs |
| User Flash Memory | 96 Kbit |
| Embedded RAM | 92 Kbit |
| FPGA Package | 132-ball BGA |
| Package Pitch | 0.5 mm |
| Programmer | LPC11U35 |
| USB Connector | USB Type-C |
| User Expansion I/O | 36 |
| User LEDs | 8 |
| RGB LEDs | 2 |
| 7-Segment Display | 2 digits |
| DIP Switches | 4 |
| Push Buttons | 4 |
| Interfaces | SPI / I2C / UART / GPIO |
| Board Dimensions | 52 × 18 mm |

## Onboard Programmer

The STEP-MXO2-C integrates an **LPC11U35-based FPGA programmer**, simplifying FPGA development without requiring an external programming adapter.

A single USB Type-C connection supports:

- Board power
- FPGA configuration programming
- UART communication with a host computer

This integrated design makes the board suitable for portable development, education, and rapid prototyping.

## Development Environment

The board supports FPGA development using **Lattice Diamond**.

Supported hardware description languages include:

- Verilog HDL
- VHDL

Typical development workflow:

1. Create an FPGA project in Lattice Diamond.
2. Select the LCMXO2-4000HC-4MG132 target device.
3. Write or import HDL source files.
4. Configure pin assignments and design constraints.
5. Synthesize and implement the FPGA design.
6. Generate the FPGA configuration file.
7. Program the board using the supported LPC11U35 programming workflow.

Detailed programming instructions and examples can be added to this repository.

## Onboard Peripherals

### LEDs and Displays

The board includes:

- 8 individual user LEDs
- 2 RGB LEDs
- 2-digit 7-segment display

These peripherals are useful for counters, PWM control, display multiplexing, and basic digital logic experiments.

### User Inputs

- 4 push buttons
- 4 DIP switches

They can be used for digital input experiments, state-machine control, and interactive FPGA applications.

### Expansion Interfaces

The board provides 36 user expansion I/Os for connecting external hardware.

Possible applications include:

- SPI peripherals
- I2C sensors
- UART communication
- GPIO expansion
- Custom digital interfaces

## FPGA Learning Projects

The STEP-MXO2-C is suitable for a wide range of experiments:

| Level | Example Projects |
|---|---|
| Beginner | LED blinking, button inputs, DIP switches |
| Beginner | Binary counters and 7-segment displays |
| Intermediate | PWM and RGB LED control |
| Intermediate | UART communication |
| Intermediate | SPI and I2C controllers |
| Intermediate | Finite-state machines |
| Advanced | Custom digital peripherals |
| Advanced | Soft-core CPU experiments |
| Advanced | Resource-compatible RISC-V implementations |

## Factory Test

The board includes a factory test design for checking basic hardware functionality.

The test demonstrates:

- LED sequencing effects
- RGB LED color effects
- 7-segment display operation
- Push-button inputs
- DIP-switch inputs
- Adjustable animation speed
- Adjustable LED brightness

## Documentation

Documentation and development resources will be organized in this repository as they become available.

Planned documentation includes:

- Hardware overview
- Pinout reference
- Programming instructions
- FPGA example projects
- Troubleshooting guide

## Purchase

The STEP-MXO2-C FPGA Development Board is available through the Nova Step Tech store on Tindie.

**[Purchase STEP-MXO2-C on Tindie](https://www.tindie.com/products/novasteptech/machxo2-fpga-board-with-lpc11u35-programmer/)**


## Copyright and License

Copyright © 2026 Nova Step Tech. All rights reserved.

Unless otherwise explicitly licensed, the hardware designs, firmware, documentation, and other original materials in this repository are proprietary to Nova Step Tech.

---

**Developed by [Nova Step Tech](https://www.tindie.com/stores/novasteptech/)**

*Making FPGA development more accessible.*
