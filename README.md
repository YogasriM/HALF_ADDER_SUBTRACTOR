# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/
HALF ADDER:  ![Screenshot 2024-12-06 044601](https://github.com/user-attachments/assets/c456477e-68d3-4a54-b3df-119da78d558e)

HALF SUBTRACTER:  ![Screenshot 2024-12-06 045947](https://github.com/user-attachments/assets/afd4c6e5-b3b0-4377-86c3-ee01ba4743ff)

**RTL Schematic**
HALF ADDER:  ![Screenshot 2024-12-06 045014](https://github.com/user-attachments/assets/efd81f99-35b1-49a2-b415-91f64bcc51a0)
HALF SUBTRACTER:  ![Screenshot 2024-12-06 050535](https://github.com/user-attachments/assets/b784b746-6a1e-4896-8b6d-f3cb9481363f)

**Output/TIMING Waveform**
HALF ADDER:  ![Screenshot 2024-12-06 044546](https://github.com/user-attachments/assets/26bfe09d-c3ad-4e05-be96-bece28280f36)
HALF SUBTRACTER:  ![Screenshot 2024-12-06 050155](https://github.com/user-attachments/assets/abbb132e-c9bc-4983-a458-6abfb9d7787d)

**Result:**
HALF ADDER:  ![Screenshot 2024-12-06 044629](https://github.com/user-attachments/assets/2c38998c-7f36-4c99-988f-1f1021ddbb97)
HALF SUBTRACTER:  ![Screenshot 2024-12-06 050236](https://github.com/user-attachments/assets/b142c1d9-5805-41ba-a42f-49ba0aeb9a7f)
