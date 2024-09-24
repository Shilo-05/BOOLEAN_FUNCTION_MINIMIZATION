# BOOLEAN_FUNCTION_MINIMIZATION

#### Developed by: Oswald Shilo
#### Reg No: 212223040139


## **AIM:**
To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## **Equipment Required:**

**Hardware – PCs, Cyclone II , USB flasher**

**Software – Quartus prime**

## **Theory**:
* Boolean Function Minimization:
Simplifies Boolean expressions to optimize hardware design and improve efficiency.

* Logic Gates:
Boolean expressions are realized using fundamental logic gates like AND, OR, and NOT.

* Verilog:
A hardware description language used to model, simulate, and synthesize digital circuits.

* Quartus Software:
Used for designing, compiling, and verifying FPGA implementations of logic functions.

* RTL Schematic:
Displays the hardware structure of the Boolean function, helping in understanding the circuit's operation.


## **Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## **Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
module ex2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule
```
```
module ex2m2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule
```

**RTL realization**

**Output:**

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

