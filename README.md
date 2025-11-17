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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
 ```

i)
module boolean(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module bool(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by: ISHWARYA M
RegisterNumber: 25011836


**RTL realization**
<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/62aea59a-0099-436e-868a-daf831d5d507" />
<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/f57c8d99-f405-41a2-9f09-7ad19da7f637" />


**Output:**

**RTL**
<img width="1920" height="1080" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/3a5beb80-5510-42d5-b036-0cedae5303c2" />
<img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/63666c00-35c2-44c2-8b20-9b8848a564a0" />


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

