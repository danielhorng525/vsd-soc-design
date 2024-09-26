# VSD-Digital_VLSI_SoC_Planning

## Background Knowledge

### Section1
<details>
  <summary>
Expand or Collapse
  </summary>

#### Package

Package: In electronics, a package refers to the physical housing that contains a semiconductor device, such as a processor or memory chip. It protects the chip and provides connections (pins or balls) for it to interface with a circuit board.

#### Chip
A chip (or integrated circuit, IC) is a small piece of semiconductor material (usually silicon) embedded in a circuit. It can contain millions or billions of transistors and other electronic components to perform various tasks, such as processing data or storing information.

![chip_pads_core_die](https://github.com/user-attachments/assets/aed31709-f86d-426f-9ed2-bb69b49a9575)

Pads: Pads are small metal areas on a chip's edge or surface that connect it to external circuits, such as the package or printed circuit board (PCB). These serve as the interface points for power, ground, and signal connections.

Core: The core is the processing unit within a chip that performs the actual computational tasks. A chip may have multiple cores (multicore) for handling multiple tasks simultaneously. Each core typically contains components like the arithmetic logic unit (ALU) and control unit.

Die: The die is the piece of semiconductor material (usually silicon) on which the circuits and transistors of the chip are fabricated. It contains the integrated circuits and is housed within the chip package. The die is where all the processing happens.

#### IPs and Macros

![IPs_Macros](https://github.com/user-attachments/assets/9dd3c48d-b7ea-4849-a53b-4e52398dda56)

IPs (Intellectual Properties): In chip design, IP blocks or IPs refer to pre-designed and pre-verified reusable functional units or modules, such as processors, memory controllers, or communication interfaces. These blocks are licensed from third parties or developed in-house and can be integrated into a larger chip design. IPs help reduce development time and cost since they don't need to be designed from scratch.

Macros: Macros in chip design are larger pre-defined blocks of logic, often referring to standard cells (like logic gates) or larger functional units (e.g., SRAMs or clock generators). These are typically pre-characterized blocks optimized for performance, area, or power that can be easily placed into the chip layout. Macros can be thought of as physical building blocks within a chip.

#### ISA

The ISA is the set of instructions that a processor can execute. It defines how software interacts with the hardware, specifying the machine code instructions that the CPU understands. Examples include x86, ARM, and RISC-V ISAs.

![SW_to_HW](https://github.com/user-attachments/assets/a3b3a79a-2958-4728-88a4-ef8bdc3d8ef1)

#### Open-source Implementation

#### OpenLANE Open-source ASIC Design Implementation Flow

#### Implementation
