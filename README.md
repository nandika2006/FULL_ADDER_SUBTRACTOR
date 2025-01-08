**NAME:NANDIKA S**


**REGISTRATION NUMBER:24010030**

## EXPERIEMENT-4 Implementation of FULL ADDER SUBTRACTOR

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

![image](https://github.com/user-attachments/assets/24a165b9-62dd-4b84-806a-9055e0410b50)

FULL SUBTRACTOR 
![image](https://github.com/user-attachments/assets/680f0333-abc8-4efe-ad5c-17f6116b8165)


**Procedure**

**Full Adder:**

    1.Open Quartus II and create a new project.
    2.Use schematic design entry to draw the full adder circuit. 
    3.The circuit consists of XOR, AND, and OR gates. 
    4.Compile the design, verify its functionality through simulation. 
    5.Implement the design on the target device and program it.

**Full Subtractor:** 

    1.Follow the same steps as for the full adder. 
    2.Draw the full subtractor circuit using schematic design. 
    3.The circuit includes XOR, AND, OR gates to perform subtraction. 
    4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program:**

![image](https://github.com/user-attachments/assets/db33db3f-5736-411f-858b-3a071b9ff75c)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: RegisterNumber:24010030
*/

**RTL Schematic**

![image](https://github.com/user-attachments/assets/dd0f9752-81b6-4bb3-8db2-5d740b806f73)


**Output Timing Waveform**

FULL ADDER:

![image](https://github.com/user-attachments/assets/1dc7dce4-b986-4bde-894a-6ec4f84028db)

FULL SUBTRACTOR::

![image](https://github.com/user-attachments/assets/de9fc047-101f-4680-8b60-2b9363ee70e7)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



