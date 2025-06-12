#  VScope

This repository details the control platform developed by the Power Electronics Innovation Center (PEIC) at Politecnico di Torino. This platform aims to combine rapid prototyping with powerful and power-dense hardware, while maintaining the flexibility of programmable peripherals.

Table of Contents

    Proposed Alternative
        Zynq 7000
        Control Board
        Code Generation
        VScope
        Experimental Validation

The proposed platform combines fast prototyping with powerful and power-dense hardware without compromising the flexibility of programmable peripherals. This solution integrates the Zynq7000 System on Chip (SoC) with a custom control board, code generation capabilities, and a visualization tool called VScope.

## Zynq 7000

The Zynq 7000 series System on Chip (SoC) board is a core component of this platform. It features a Dual Core CPU operating at 600-800MHz, interfaced with an 85k Programmable Logic (FPGA). This setup enables nested interrupts up to 150 kHz.
![immagine](https://github.com/user-attachments/assets/8665adae-e16d-4fea-99c8-385212f28c70)

### Control Board
![immagine](https://github.com/user-attachments/assets/52166023-1b6e-4ef5-be62-324e0b42c5b7)


The custom-designed control board provides essential functionalities:

    14-bit ADC: Operates at 2MSPS with a pm10V input range.

IOs: 5V compatible.
Encoder and CAN interfaces: Integrated for various applications.
Integrated Supply: Provides necessary power to the system.

### Code Generation

The platform is developed with code generation in mind, streamlining the development process. It supports automatic C/C++ code generation from Simulink models. This allows for efficient creation and verification of code for the control system.

## VScope

VScope is a real-time visualization tool that allows users to visualize, modify and store data. It offers customizable plotting and display options for various data channels.


https://github.com/user-attachments/assets/b7250e2a-f500-4662-91ba-23ea3ce8e45a

## Experimental Validation

The platform has been hooked up to a GaN Buck converter at Power Electronics Innovation Centre of Politecnico di Torino. ![ti mk2--00004](https://github.com/user-attachments/assets/e3664317-d14a-4f03-b3c1-55a6cc038b71)
