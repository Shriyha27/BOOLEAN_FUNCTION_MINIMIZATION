# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2024-10-14 at 14 06 02_82a55775](https://github.com/user-attachments/assets/4faa63f1-a124-4f5c-9247-a2796541ebdd)

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

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




Developed by: RegisterNumber: 24007606

**Output:**

**RTL realization**![EXP_3_1](https://github.com/user-attachments/assets/6df1c729-da63-4689-9345-896b561aadc5)

![EXP_3_2](https://github.com/user-attachments/assets/7f241857-a9e5-4d67-b81a-1db0351e37ff)


**Timing Diagram**![Waveform3_1](https://github.com/user-attachments/assets/0b7350cd-6576-4854-8c38-ab07b5b10e69)

![Waveform3_2](https://github.com/user-attachments/assets/8a1ed604-9efd-4c70-809a-236485f1b441)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

