# ARITHMETIC-LOGIC-UNIT-ALU---1

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: JOSHITHA AGURU

**INTERN ID**: CT08HFQ

**DOMAIN**: VLSI

**BATCH DURATION**:  December 30th, 2024 to January 30th, 2025

**MENTOR NAME**: NEELA SANTHOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS

An Arithmetic Logic Unit (ALU) is a fundamental digital circuit used in processors to perform arithmetic and logical operations. This design focuses on a 4-bit ALU capable of performing five primary operations: Addition, Subtraction, AND, OR, and NOT.

1. ALU Design Overview

The ALU takes two 4-bit inputs (A and B) and a 3-bit control signal (ALU_Sel) to determine the operation. The outputs include a 4-bit result (ALU_Out) and a CarryOut signal to handle overflow in arithmetic operations.

2. Operations Performed

Addition (ALU_Sel = 000): Adds two 4-bit numbers, producing a result and a carry-out flag if the result exceeds 4 bits.

Subtraction (ALU_Sel = 001): Subtracts the second input (B) from the first input (A), handling borrow if necessary.

AND (ALU_Sel = 010): Performs a bitwise AND operation on inputs A and B.

OR (ALU_Sel = 011): Performs a bitwise OR operation on inputs A and B.

NOT (ALU_Sel = 100): Performs a bitwise NOT operation on input A.


3. Testbench Overview

A testbench module is created to verify the ALU's functionality. It applies different test cases for each operation, waits for results, and displays outputs using $display.

4. Simulation and Expected Results

During simulation:

Addition and Subtraction display results and carry-out signals.

AND and OR show the bitwise results of the operations.

NOT operation inverts all bits of input A.


For example:

Addition (5 + 3): 1000

Subtraction (9 - 4): 0101

AND (1100 & 1010): 1000

OR (1100 | 1010): 1110

NOT (~1111): 0000


5. Conclusion

This ALU design demonstrates essential arithmetic and logical operations, making it a foundational building block for more complex processor architectures. The code is modular, easy to test, and can be extended for additional operations.


**output**
![Gallery_1735716226598](https://github.com/user-attachments/assets/2a8e01e1-87a8-4a5e-97af-906bc2f89066)
