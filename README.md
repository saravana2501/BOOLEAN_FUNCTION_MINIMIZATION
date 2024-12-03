**EXP2:BOOLEAN FUNCTION MINIMIZATION**

NAME: SARAVANA KUMAR

REF NO:24900200

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module booleanminimization(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule



**RTL realization**

![boolean minimization waveform screenshot](https://github.com/user-attachments/assets/0097b45f-aef3-4c8d-b427-03f56ad4e766)


**RTL**

![boolean minimization screenshot](https://github.com/user-attachments/assets/e66714ae-8f95-4c53-b548-e572245bfac1)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

