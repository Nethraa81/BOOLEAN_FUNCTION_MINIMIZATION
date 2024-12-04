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

Developed by : N.NETHRAA 

REGISTER NUMBER : 24900193

```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization**

![de rtl 2](https://github.com/user-attachments/assets/aea9b71f-5510-4991-92c0-0ca3ea953fd6)



**Output:**

**RTL**

**TIMIMNG DIAGRAM**

![de waveform 2](https://github.com/user-attachments/assets/e9b7b1a6-42aa-49ce-a6e6-5a9911875d54)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

