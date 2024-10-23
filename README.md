# Multi-cycle Implementation of a CPU Microcontroller 🚀

## Overview

This project involves designing and verifying a simple pipelined RISC processor. It is implemented in Verilog and structured around a 16-bit instruction set architecture, operating in a pipelined architecture to enhance processing efficiency. This design was created as part of the ENCS4370 Computer Architecture course.

## Last Updated

📅 Last updated: October 23, 2024

## Specifications 🛠️

### General Specifications
- **Word Size:** 16 bits
- **Registers:** 8 general-purpose registers, R0 to R7 with R0 permanently zeroed.
- **Memory:** Separately allocated instruction and data memories, enhancing the data handling efficiency.
- **Endianness:** Little endian format used for byte ordering.

## Features 🌟

- **Pipelined Architecture:** Implements a 5-stage pipeline enhancing the processor's performance and throughput.
- **Verilog Implementation:** The entire processor is implemented in Verilog, showcasing modular design and effective use of simulation tools.
- **Instruction Set:** Supports a comprehensive set of instructions tailored to demonstrate basic arithmetic, logic, and control operations.


## Simulation and Testing 🧪

Ensure every instruction and feature of the processor operates correctly under all specified conditions:

- **Functional Testing:** Each instruction type is tested for correctness.
- **Performance Metrics:** Pipeline efficiency is analyzed, and potential stalls are identified and mitigated.
  

## Challenges and Lessons Learned 🚧

Throughout the development of this processor, we encountered several challenges:

- **Pipeline Hazards:** Managing and mitigating data hazards required careful design of forwarding and hazard detection units.
- **Control Logic Complexity:** Implementing the control logic to handle various instruction types tested our understanding and application of digital logic.

These challenges deepend my understanding of computer architecture and Verilog programming.

## What's Next? 🔮

Looking ahead, there are several enhancements and expansions planned for the RISC processor project:

- **Support for Additional Instructions:** We plan to extend the instruction set to include more complex operations and possibly introduce support for floating-point calculations.
- **Performance Optimization:** Investigating opportunities for optimizing the existing pipeline to reduce latency and increase throughput.
- **Testing and Verification:** Creating comprehensive testbenches to cover all possible scenarios proved to be the most intricate part of the project.


## Contributors 👥

This project was developed by Sy Hassouneh and Sondos Qasarwa, students of the Department of Electrical and Computer Engineering.

## Docuentation

For full documentation of the project, please see the attached PDF: [Link_to_PDF]


## Installation and Setup 📦

### Prerequisites

Before you begin, ensure you have the Active-HDL Student Edition installed for Verilog simulation. This software is crucial for simulating and testing the processor design you will be working with.

- You can download the Active-HDL Student Edition from [Aldec's official website](https://www.aldec.com/en/products/fpga_simulation/active_hdl_student).
- Follow the installation guide on the website to set up Active-HDL on your system.
