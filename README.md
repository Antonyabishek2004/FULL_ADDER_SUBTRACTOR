# DEVELOPED BY : ANTONY ABISHEK

# REGISTER NUMBER : 212223240009

# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

# Procedure

Write the detailed procedure here

# Program:

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

DEVELOPED BY : ANTONY ABISHEK 

REGISTER NUMBER : 212223240009
*/

![EX NO 4 (DIGITAL ELECTRONICS )PICS](https://github.com/user-attachments/assets/1b49e508-e97a-4db4-a8b9-9ac41842ce21)

![image](https://github.com/user-attachments/assets/ba8bff6c-f3e9-4e42-bf57-a887c71eac03)

# RTL Schematic

![image](https://github.com/user-attachments/assets/d4baa1ad-bcf6-4bea-ae37-37b75d3e4ac3)

![image](https://github.com/user-attachments/assets/51dbd706-3fcb-49cf-a2e2-cc71c800b5b4)

# Output Timing Waveform

![image](https://github.com/user-attachments/assets/f995fa00-b200-4cb3-a2f8-11ad38c97891)

![image](https://github.com/user-attachments/assets/1c569991-b7b6-4044-a911-68bc147c4adf)

# Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



