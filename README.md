# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```
Developed by: BHAVANISHA.M RegisterNumber: 25018505


**RTL realization**

<img width="903" height="473" alt="image" src="https://github.com/user-attachments/assets/07775647-034a-4e26-bac9-f9e6cb5f6f4f" />



**Timing Diagram**
<img width="1600" height="860" alt="image" src="https://github.com/user-attachments/assets/0a8c8f11-9c9d-45df-8206-fd0f3d8ddcb2" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

