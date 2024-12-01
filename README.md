# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-12-01 at 9 19 34 PM](https://github.com/user-attachments/assets/18da6e6b-3e43-4a83-bc2d-9fa4076cc182)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Abhinav.C.S RegisterNumber: 24001247

module exp2booleanfunctionminimization(a,b,c,d,f1,w,x,y,z,f2);
 input a,b,c,d,w,x,y,z;
 output f1,f2;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 assign f2=((~y&z)|(x&y)|(w&y));
 endmodule

**RTL realization**
![WhatsApp Image 2024-12-01 at 9 40 17 PM](https://github.com/user-attachments/assets/5fb2753e-9200-40c4-ab37-1528c5f4a85d)


**Output:**

**RTL**

**Timing Diagram**
![WhatsApp Image 2024-12-01 at 9 40 17 PM (1)](https://github.com/user-attachments/assets/6d12921c-dc18-46cf-9b5c-c1f69fda7d53)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

