# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions.


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
i)
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


Developed by: Hemalatha

RegisterNumber:24901252


**RTL**

![ADD](https://github.com/user-attachments/assets/233b82f0-d755-4a30-8b5e-a8baa034beff)

![SUB](https://github.com/user-attachments/assets/2f9ab589-4183-46da-bb39-8caaea6c2ebd)



**OUTPUT**

![ADD WAVEFORM](https://github.com/user-attachments/assets/b0c45544-62eb-4c45-9ec8-cb38958bf632)

![SUB WAVEFORM](https://github.com/user-attachments/assets/3fc0a20b-0793-4def-a95c-6658d1a46553)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

