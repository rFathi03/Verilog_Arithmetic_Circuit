# Verilog HDL Code for 3-Bit Arithmetic Circuit

## Overview
Welcome to the Verilog HDL code repository for a 3-bit arithmetic circuit! In this project, we've implemented a circuit that performs arithmetic operations based on selection inputs and signed 3-bit integers.

## Requirements
To meet the project specifications, we adhered to the following guidelines:

1. Utilized a minimal set of components: Full-adders, 4x1 Multiplexers, 2x1 Multiplexers, OR, AND, NOT, XOR gates.
2. The Verilog code includes a comment at the beginning, specifying the types and quantity of components used.
3. Multiplexers were implemented using structural Verilog descriptions.
4. Input includes two selection inputs and two signed integers (A and B) in 3-bit 2's complement form.
5. Output is a signed 3-bit integer (G) in 2's complement form.
6. Operational logic:
   - When selection inputs are 00, G = A + 1.
   - When selection inputs are 01, G = A + B.
   - When selection inputs are 10, G = B - A.
   - When selection inputs are 11, G = 1 - B.

## Implementation Details
The Verilog code is structured to fulfill the outlined requirements, ensuring efficient use of components while maintaining functionality. A detailed comment at the beginning of the code provides insights into the design choices made.

## Test Bench
To validate the robustness of our implementation, we've included a comprehensive test bench with 40 test cases. These test cases cover various input values and scenarios, thoroughly examining the circuit's performance under different conditions.

## Collaborators 
- [Roaa Fathi](https://github.com/rFathi03)

- [Selsabeel Asim](https://github.com/SelsabeelA)

- [Basma Mahmoud](https://github.com/Basma2423)

- [Nourhan Mahumoud](https://github.com/NourhanMahmoudd)

- [Howida Adel Abd El-Halim](https://github.com/howidaabdelhalim)
