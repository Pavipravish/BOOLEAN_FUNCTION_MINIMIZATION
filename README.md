# BOOLEAN_FUNCTION_MINIMIZATION

EXP-2

DATE-1-10-2024

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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. */
 **program f1**
 
 module logic1(a,b,c,d,f1);
 
 input a,b,c,d;
 
 output f1;
 
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 
 endmodule

**program f2**
 
 module logic3(w,x,y,z,f2);
 
 input w,x,y,z;
 
 output f2;
 
 assign f2=((~y & z)|( w & y )|(x & y));
 
 endmodule

Developed by:Pravish j

RegisterNumber:24901067

**Output:**

**RTL realization**

![image](https://github.com/user-attachments/assets/8f1ff8da-efc0-40c8-a9fd-e3dd7d73df96)

**Timing Diagram**

![image](https://github.com/user-attachments/assets/e21c06b0-2900-49d8-8c0f-a511aac5d865)

**PROGRAM F2**

**RTL realization**

![image](https://github.com/user-attachments/assets/b7ffc502-77fb-4ae6-83be-0d6b1db9e853)


**Timing Diagram**

![image](https://github.com/user-attachments/assets/20fcf71c-388f-42c3-8e9e-8c2f9917b9ad)

**TRUTH TABLE**

![image](https://github.com/user-attachments/assets/96cbf89e-238f-4af4-9683-1f2b26cf3817)

![image](https://github.com/user-attachments/assets/89173674-e0df-481f-bd4f-23a7b8059b0b)

**BOOLEAN MINIMIZATION**

![image](https://github.com/user-attachments/assets/5504919a-b017-4248-87bb-a025872b982f)

![image](https://github.com/user-attachments/assets/60ed48fb-7897-4feb-bb52-ff99842fadef)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
