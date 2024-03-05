# As per the Update given for the next task "Should Use the RISC-V Core Verilog netlist and testbench for functional Simulation.
# Veriog code is being executed and the waveforms are generated using the gtkwave
# Aim: To verify the Functional Simulation:-
# Table of contents
- [1.RISC-V RV32I](#1-RISC-V-RV32I)
 - [2.BLOCK DIAGRAM OF RISC-V RV32I](#2-BLOCK-DIAGRAM-OF-RISC-V-RV32I)
 - [3.INSTRUCTION SET OF RISC-V RV32I](#3-INSTRUCTION-SET-OF-RISC-V-RV32I)
 - [4.FUNCTIONAL SIMULATION](#4-FUNCTIONAL-SIMULATION)
    - [4.1 About iverilog and gtkwave](#41-About-iverilog-and-gtkwave)
    - [4.2 Installing iverilog and gtkwave](#42-Installing-iverilog-and-gtkwave)
    - [4.3 The output waveform](#43-The-output-waveform)
  
1. RISC-V RV32I
This project provides an insight into the working of a few important instructions of the instruction set of a Single cycle Reduced Instruction Set Computer - Five(RISC-V) Instruction Set Architecture suitable for use across wide-spectrum of Applications from low-power embedded devices to high-performance Cloud-based Server processors. The base RISC-V is a 32-bit processor with 31 general-purpose registers, so all the instructions are 32-bit long. Some Applications where the RISC-V processors have begun to make some significant threads are in Artificial intelligence and machine learning, Embedded systems, ultra-low power processing systems, etc.

2. BLOCK DIAGRAM OF RISC-V RV32I
 ![iv1](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/a93b3d1b-ae1b-4439-9f03-07e21374240c)
3. INSTRUCTION SET OF RISC-V RV32I
 ![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/29a0dd4e-e613-4d47-98c6-68e939ac3932)
![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/5812855d-f067-4760-960e-4cbdf0fbe7a8)


# 4. FUNCTIONAL SIMULATION
# 4.1 About iverilog and gtkwave
 # Icarus Verilog is an implementation of the Verilog hardware description language.
 # GTKWave is a fully featured GTK+ v1. 2 based wave viewer for Unix and Win32 which reads Ver Structural Verilog Compiler generated AET files as well as standard Verilog VCD/EVCD files and allows their viewing.
# 4.2 Installing iverilog and gtkwave
> For Ubuntu
Open your terminal and type the following to install iverilog and GTKWave

  # $   sudo apt get update
  # $   sudo apt get install iverilog gtkwave
  ![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/92c505d7-2080-4c4a-8769-62996f7be060)
  To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.
  
# $ git clone https://github.com/maraputivishnusai/maraputivishnusai
# $ cd maraputivishnusai
![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/f5474d1a-1153-436c-951b-b640f86e2abf)
# To simulate and run the Verilog code, enter the following commands in your terminal

# $ iverilog -o hello hello.v hello_tb.v
# $ ./hello

![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/feadfa36-9e65-479e-834f-ce802f9466a3)


To see the output waveform in gtkwave, enter the following commands in your terminal.
# $ gtkwave hello.vcd

![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/7eaed4e7-85e6-4a6c-a8a4-377a5d125491)

# 4.3 The output waveform
The output waveform showing the instructions performed in a 5-stage pipelined architecture.

![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/c4f5cb7f-3e77-40d9-b0bc-3adc7be32804)

![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/faca79f3-04e2-46be-92eb-de02aeaae8a3)

![image](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/953ed898-076b-4d8c-9a3e-6952c5e0b3c0)


