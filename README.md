**NAME:JENITTAN JOSE J B**

**REG NO:24006462**

**EXPNO 3:HALF ADDER AND HALF SUBTRACTOR**

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**HALF ADDER**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**HALF SUBTRACTOR**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


**PROCEDURE:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**

![Screenshot 2024-12-12 104628](https://github.com/user-attachments/assets/6a9ceb64-dd1a-4cd9-88b4-2dd0eb683aa4)

**TRUTH TABLE:**

**HALF ADDER:**

![Screenshot 2024-12-12 104940](https://github.com/user-attachments/assets/26d99bc2-86af-4c7b-9a09-6b0ef475e799)

**HALF SUBTRACTOR:**

![Screenshot 2024-12-12 105052](https://github.com/user-attachments/assets/dee36de6-eef7-4308-bdee-ebd0e2c3b60c)

**RTL Schematic:**

![Screenshot 2024-12-12 104304](https://github.com/user-attachments/assets/5d70d082-60ad-413d-93e6-7a24811a98a4)

**TIMING DIAGRAM:**

![Screenshot 2024-12-12 104533](https://github.com/user-attachments/assets/b292d8fe-75f6-4c38-8fef-a4a63860ae30)

**RESULT:**

Designed and verified the half adder & half subractor circuit and its truth table in quartus ll using Verilog programming successfully.
