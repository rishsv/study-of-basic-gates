#EX-01 Study-of-basic-gates
#DATE: 09-03-2026

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
'''
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
'''

 Developed by: Rishwanth S V RegisterNumber: 212225040338
 
**Logic symbol & Truthtable**
<img width="806" height="170" alt="398738127-1c091aee-f658-49e1-ba22-801e5dfe40bf" src="https://github.com/user-attachments/assets/1d52598d-83d8-4457-9cea-4bd94359c44f" />

**RTL realization Output:** 
<img width="891" height="812" alt="398739401-fe2a573a-2891-409c-a128-62f37e4de1f8" src="https://github.com/user-attachments/assets/55f0cb82-314a-4354-acda-ead7813bdc3d" />

**RTL**
<img width="1032" height="472" alt="398739221-3cc49cdf-35fd-440a-8ee6-40b1a0f77571" src="https://github.com/user-attachments/assets/e1df2b7d-8c21-457c-86d3-b19bd7a0ba3f" />

**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.



