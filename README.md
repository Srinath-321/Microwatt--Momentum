# Neural Engine Accelerator Proposal for Microwatt Hackathon

## Project Overview
This project suggests designing and implementing a custom **Neural Engine Accelerator** that works with the open-source Microwatt CPU core. The goal of the accelerator is to efficiently perform real-time inference of small neural networks, optimized for edge AI applications like sensor data classification. This hardware accelerator will take on neural network computations from the Microwatt CPU, enabling low-power and low-latency AI processing on embedded platforms.

Many edge computing devices need AI inference capabilities but struggle with power and performance when they depend on general-purpose processors. This project aims to fill that gap by proposing a dedicated neural engine that speeds up matrix multiplications and activation functions. This will help Microwatt-based systems handle AI tasks more effectively.

## Proposed Features
- Verilog-based neural accelerator design, focusing on fixed-point arithmetic  
- Smooth interface with the Microwatt CPU core for offloading neural computations  
- Target applications include sensor classification, anomaly detection, and low-power AI inference  
- Design will adhere to open-source practices to align with ChipFoundry’s SKY130 fabrication process  
- Detailed RTL testbenches and verification strategy planned  

## Technology Stack
- Microwatt CPU Core (OpenPOWER ISA)  
- Verilog HDL for RTL design  
- Open-source FPGA tools: Yosys, GHDL, Verilator, NextPNR  
- OpenLane chipIgnite flow for ASIC fabrication preparation  
- GCC for POWER and GDB for software development   

## AI Assistance Disclosure
Prompts and interactions will be documented here and included if applicable.

## License
This project will be released under the MIT License.
