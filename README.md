# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean function minimization refers to the process of simplifying a Boolean expression
to its most efficient form. The goal is to reduce the number of logic gates, variables, and terms needed to represent the function,
which is important for hardware design and optimization in digital circuits.

**Logic Diagram**
![WhatsApp Image 2024-12-09 at 03 48 23_67b3ddb3](https://github.com/user-attachments/assets/0c08e353-7b16-4368-aa61-7f9b6e36cdfc)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

module exp2(a,b,c,d,w,x,y,z,f1,f2);

input a,b,c,d,w,x,y,z;

output f1,f2;

assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));

assign f2=((~y&z)|(x&y)|(w&y));

endmodule

Developed by: Daniyel Antony Raj SD RegisterNumber:24002985


**RTL realization**
![WhatsApp Image 2024-12-09 at 03 48 23_a48aade7](https://github.com/user-attachments/assets/8d0262c8-7cdd-4388-a1a4-12a89d9d2647)


**Output:**
![WhatsApp Image 2024-12-09 at 03 48 24_3d4eaafd](https://github.com/user-attachments/assets/25561246-5f36-43df-9a88-a5a7e845a710)


**RTL**
![WhatsApp Image 2024-12-09 at 03 48 23_a48aade7](https://github.com/user-attachments/assets/eeef6c2c-1d12-4d90-b736-5098a5cb023a)


**Timing Diagram**
![WhatsApp Image 2024-12-09 at 03 48 24_3d4eaafd](https://github.com/user-attachments/assets/71ec11c9-527b-4c76-8cbc-9913322ab035)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

