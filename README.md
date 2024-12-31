# BOOLEAN_FUNCTION_MINIMIZATION
**DATE: 4/10/2024**

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**TRUTH TABLE**

**F1**

![image](https://github.com/user-attachments/assets/c1a358dd-9b50-403d-8126-7fac8ea60ac2)

**F2**

![image](https://github.com/user-attachments/assets/fabd3db2-a2df-4ab6-b000-23799cdedefa)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**BOOLEAN MINIMIZATION**

**F1**

![image](https://github.com/user-attachments/assets/1a0727dc-e813-4b66-898c-1c4730f8176b)

**F2**

![image](https://github.com/user-attachments/assets/b59d8e3a-22d4-4fd3-bfac-30d469fe52ae)

**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Daniyel Antony Raj SD

Register Number: 212224220018
```
i)F1
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)F2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));0
endmodule
```
**RTL DIAGRAM**

**F1**

![image](https://github.com/user-attachments/assets/a62a2ed4-e5dd-4eb1-9284-dd63c6047cf4)

**F2**

![image](https://github.com/user-attachments/assets/9ea258b7-0118-4230-beb1-386ad14ad80f)

**TIMING WAVEFORM**

**F1**

![image](https://github.com/user-attachments/assets/a1f33d10-e65d-4475-82c2-ca7afe419af2)

**F2**

![image](https://github.com/user-attachments/assets/122e0e89-19fb-47f5-a965-d4811318a682)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

