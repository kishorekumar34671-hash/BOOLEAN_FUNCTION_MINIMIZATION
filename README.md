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

```Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:KISHORE KUMAR B
RegisterNumber:25007664
```
```
module EX2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**
<img width="1166" height="725" alt="Screenshot 2026-03-10 092231" src="https://github.com/user-attachments/assets/97ec7513-d404-4d68-9e29-a32487370763" />






**RTL**
<img width="1920" height="1080" alt="Screenshot 2026-03-10 092852" src="https://github.com/user-attachments/assets/e5163504-7ae1-4b03-bec4-5477de414317" />





**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

