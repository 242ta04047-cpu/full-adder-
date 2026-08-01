# Full Adder using Verilog

## Overview

A Full Adder is a combinational logic circuit that adds three one-bit binary inputs:

- A
- B
- Carry In (Cin)

It produces two outputs:

- Sum
- Carry Out (Cout)

This project implements a Full Adder in Verilog and verifies its functionality using a testbench.

---

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 1 |

---

## Boolean Expressions

Sum = A ⊕ B ⊕ Cin

Carry = (A & B) | (B & Cin) | (A & Cin)

---

## Files

- `full_adder.v` – Verilog implementation
- `full_adder_tb.v` – Testbench
- `simulation_results.png` – Waveform screenshot
- `README.md` – Project documentation

---

## Software Used

- ModelSim
- Vivado
- Xilinx ISE
- GTKWave

---

## Expected Output

A B Cin | Sum Cout

0 0 0 | 0 0

0 0 1 | 1 0

0 1 0 | 1 0

0 1 1 | 0 1

1 0 0 | 1 0

1 0 1 | 0 1

1 1 0 | 0 1

1 1 1 | 1 1

---

## Applications

- Arithmetic Logic Unit (ALU)
- Binary Adders
- Multipliers
- Digital Processors
- CPUs

---

## Author

Your Name