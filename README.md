# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Sanjay kumar H

RegisterNumber:  23011170

Code:

Half Adder:

![Exp3 ha code](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/cc1a7ed9-b1b3-4739-8a64-b948ad5ed953)

Full Adder:

![Exp3 fa code](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/ae2e9683-554c-47c2-aeb2-e27dac73d6ad)

Truth Table:

Half Adder:

![Exp3 truthtable (ha)](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/e227b5bd-7f9e-460a-a038-0e2464d3549b)

Full Adder:

![Exp3 truthtable (fa)](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/d957e4b0-11af-4cbc-ad8d-cc5f2c6bf2c9)


RTL Diagram:

Half Adder:

![Exp3 ha RTL diagram](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/beb67eec-069d-49f1-8a4b-152951c73342)

Full Adder:

![Exp3 fa RTL diagram](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/c6fa71b1-a77a-4303-b624-71b03f6ddb31)

Output:

Full Adder:

![Exp3 fa wave](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/c47b5ba4-0d53-43cb-97b8-0ed2068361b0)

Half Adder:

![halfadder-wave](https://github.com/Sanjaykumar0924/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144149258/e87008c0-8187-4c98-8995-754b443904dc)









### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full
adder are verified
