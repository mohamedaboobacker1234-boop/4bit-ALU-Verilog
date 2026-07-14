# 4bit-ALU-Verilog
4-bit Arithmetic Logic Unit (ALU) designed using Verilog HDL with simulation in Icarus Verilog and waveform verification using GTKWave.


# 4-Bit ALU using Verilog

## Overview

This project implements a 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL.

The ALU performs basic arithmetic and logical operations based on a 3-bit selection input. The design was simulated using Icarus Verilog and verified using GTKWave.

---

## Features

- 4-bit Inputs
- 4-bit Output
- 3-bit Select Line
- Combinational Logic Design
- Simulation using Icarus Verilog
- Waveform Verification using GTKWave

---

## Operations

| Select | Operation |
|---------|-----------|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | XOR |
| 101 | NAND |
| 110 | NOR |
| 111 | NOT (A) |

---

## Tools Used

- Verilog HDL
- Visual Studio Code
- Icarus Verilog
- GTKWave

---

## Project Structure

```
4bit-ALU-Verilog
│
├── alu.v
├── alu_tb.v
├── alu.vcd
├── waveform.png
└── README.md
```

---

## Simulation

Compile

```
iverilog -o alu alu.v alu_tb.v
```

Run Simulation

```
vvp alu
```

Open GTKWave

```
gtkwave alu.vcd
```

---

## Sample Waveform

(Add your GTKWave screenshot here.)

---

## Learning Outcomes

Through this project, I learned:

- Verilog module design
- Combinational logic
- Case statements
- Binary number representation
- Testbench creation
- Simulation using Icarus Verilog
- Waveform analysis using GTKWave

---

## Future Improvements

- Carry Flag
- Zero Flag
- Overflow Flag
- Negative Flag
- Parameterized ALU Width
- SystemVerilog Testbench

---

## Author

Mohamed Aboobacker M

Electronics and Communication Engineering (ECE)

Learning RTL Design and VLSI Design
