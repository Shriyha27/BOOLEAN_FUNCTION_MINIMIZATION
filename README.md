# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2024-10-28 at 14 26 37_c47d1597](https://github.com/user-attachments/assets/1bfc1b12-3df1-47c5-a6f9-798d3aee510a)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

module EXP_3_1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
module EXP_3_2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24007606


**Output:**

**RTL** ![EXP_3_1](https://github.com/user-attachments/assets/33482617-a682-4fc3-a4da-7c93ec798c99)
![EXP_3_2](https://github.com/user-attachments/assets/75ae99ba-182a-4e6e-afcc-f1983618693b)



**Timing Diagram** ![Waveform3_1](https://github.com/user-attachments/assets/9b68edb2-d7aa-4746-9606-4fca283e5d56)
![Waveform3_2](https://github.com/user-attachments/assets/7d95c9a3-6d15-4897-b4f3-79863738160c)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

