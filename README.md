# T006 Datapath Circuit

This project implements the datapath of a simple processor using Logisim, designed to demonstrate key principles of computer architecture and digital logic design.

---

## Overview
The datapath represents the hardware components and connections responsible for executing instructions within a CPU.  
This circuit models how data moves between registers, memory, and the Arithmetic Logic Unit (ALU), controlled by multiplexers and timing signals.

---

## Components
- **ALU (Arithmetic Logic Unit)** — performs arithmetic and logical operations  
- **Registers** — temporary data storage for operands and results  
- **Register File** — enables simultaneous read/write access  
- **Multiplexers** — control data flow between components  
- **Memory Units** — for load and store operations  
- **Control Signals** — synchronize and direct operations across the datapath  

---

## Objectives
- Understand how CPU datapaths process instructions at the hardware level  
- Explore control signal interactions and timing synchronization  
- Provide a foundation for integrating a Control Unit and Instruction Memory to form a complete processor  

---

## Tools Used
- Logisim / Logisim Evolution — for circuit simulation and design visualization  

---

## File Included
- `T006_datapath.circ` — the main datapath circuit file  

---

## How to Run
1. Open the `T006_datapath.circ` file in Logisim Evolution.  
2. Power the circuit using the clock input.  
3. Observe data movement through registers, ALU, and memory.  
4. Experiment with inputs to simulate instruction execution.  

---

## Learning Outcomes
- Gain hands-on experience with digital hardware design  
- Understand the core of CPU operations — the datapath  
- Visualize how instructions are executed step-by-step in hardware  
