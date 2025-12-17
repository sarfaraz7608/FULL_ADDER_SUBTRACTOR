# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:25015425
**RTL Schematic**
```
full adder
```
<img width="1920" height="1080" alt="Screenshot 2025-12-17 104147" src="https://github.com/user-attachments/assets/3acf01d4-4097-4d37-9eff-d3242a179bf3" />
```
full subtracter
```
<img width="1920" height="1080" alt="Screenshot 2025-12-17 104320" src="https://github.com/user-attachments/assets/6af7c711-4465-4e1e-9857-d527bb44791d" />

**Output Timing Waveform**
```
full adder
```
<img width="1920" height="1080" alt="Screenshot 2025-12-17 104627" src="https://github.com/user-attachments/assets/79d049fa-bab1-4147-88c0-f2ff9a286779" />

```
full subtractor
```
<img width="1920" height="1080" alt="Screenshot 2025-12-17 104838" src="https://github.com/user-attachments/assets/f972fe39-2fcb-45e3-a2d0-48bfd2785b1e" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



