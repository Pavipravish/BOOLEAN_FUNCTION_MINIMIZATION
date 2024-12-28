
### EXPERIMENT-2-BOOLEAN_FUNCTION_MINIMIZATION

DEVELOPED BY: PRAVISH.J
REG NO:2401067


**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**THEORY:**

Implementing Boolean functions in Verilog HDL (Hardware Description Language)
involves translating the simplified Boolean expressions into Verilog code to describe the
behavior of digital circuits. The basic building blocks in Verilog is module. The module
represent a combinationa circuit. Use logical operators (&, , ~, ^) to implement Boolean
functions directly. Use built-in gate primitives for basic functions: Use University
program VWF to verify the functionality of your Verilog modules. Create waveform and
check outputs against expected results.



**PROCEDURE:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

developed by: pravish.J 
Reg no: 24901067

**PROGRAM:**


module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

2;
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule


**RTL REALIZATION:**




![Screenshot 2024-12-12 102714](https://github.com/user-attachments/assets/5da34538-e3a3-4a7f-9fa8-5472d6729833)

**TIMING DIAGRAM:**


![Screenshot 2024-12-12 173231](https://github.com/user-attachments/assets/9397b919-7ad6-410a-aa88-af9d370a38f5)

**RESULT:**

Thus the given logic functions are implemented using QUARTUS and their operations are verified using Verilog programming.
