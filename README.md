# EX-01 Study-of-basic-gates
# DATE: 09-03-2026

### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**PROGRAM**
~~~
module LogicGates1(a,b,c);
input a;
input b;
output [6:0] c;
assign c[0]=a&b;
assign c[1]=a|b;
assign c[2]=~(a&b);
assign c[3]=~(a|b);
assign c[4]=a^b;
assign c[5]=~(a^b);
assign c[6]=~a;
endmodule 
~~~

Developed by: Rishwanth S V 
Register Number: 212225040338
 
**Logic symbol & Truthtable**
![380988021-11d6b227-e8ce-425b-9e42-faf0f90ac403](https://github.com/user-attachments/assets/402be786-5488-4396-9dc9-d8cd47b790b1)

**RTL realization Output:** 
![380988101-cb08bdd4-25cf-4e78-9abd-c4d98eb0d5c7](https://github.com/user-attachments/assets/b78f12a6-c95d-4300-8c19-4788e0c8b947)

**RTL**
<img width="1920" height="1200" alt="380988152-a475b1fc-6f6c-4df9-b933-000cd037bbab" src="https://github.com/user-attachments/assets/bf2816b9-1968-46c4-8a95-6723917c762a" />


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.



