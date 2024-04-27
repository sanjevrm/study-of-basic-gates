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

Program for logic gates and verify its truth table in quartus using Verilog programming

# Developed by: Sanjev R M
# register no: 212223040186
# program:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/0c473722-75e4-4b30-9b3b-067a6d7e7580)

# Logic symbol & Truthtable
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/3085ccb5-c6fc-49e6-b0dd-d46990020e68)

# RTL
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/1dfcc0a2-4570-42f4-92e1-b7b83f9531c4)

# RTL realization Output:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/9492bec6-a138-4e21-b696-acf9aa178295)


# OR GATE:
# program:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/ed657b84-097b-4fba-b5a3-7c4c597b00b8)

# Logic symbol & Truthtable:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/fe0fcd80-cd3b-4c86-ab81-d59856357002)

# RTL:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/0cfdaa78-246a-4a3c-940e-1fbc1f97a993)

# RTL realization Output:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/9a3107d1-a134-46b3-abe9-79d258e9010e)

# NOT GATE:
# program:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/2fb772a3-a108-45af-b98d-ac6dd898bd66)

# Logic symbol & Truthtable:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/018ae510-51e9-4d37-a5bf-6cd77eaaa821)

# RTL:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/1c925604-357d-4847-a1a2-e445cd1859fb)


# RTL realization Output:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/8281c18c-75d3-47fe-99a9-167b711fbbc4)

# NAND GATE:
# program:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/a47ff0ac-1685-4e5d-bf03-1d24c14c3da5)

# Logic symbol & Truthtable:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/6b9ea207-6336-465f-a4a7-4cd137cd615c)

# RTL:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/a2dd18ac-5d64-48f9-8b89-aeb3fb3bd19e)


# RTL realization Output:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/be227915-aecb-4540-a315-79df22d476cb)

# NOR GATE:
# program:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/a56dfc95-8784-4d82-91e7-ea78d590a133)

# Logic symbol & Truthtable:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/d107d02d-de69-4049-8b33-5c650765be29)

# RTL:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/ee0c5c4d-7e6c-49ee-8148-51cb23d3cce5)

# RTL realization Output:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/73f89ee7-8b11-4274-979e-7dfa905269eb)

# EX-OR GATE:
# program :
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/aa987922-cead-4df3-a9a7-876a80283fa4)

# Logic symbol & Truthtable:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/53db8115-999f-408e-a24b-e20b8783f65d)

# RTL:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/792b8221-1175-44dd-ae7c-f47dcb19dc41)

# RTL realization Output:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/4ab9f4b6-f8ac-4307-8baa-8bda7785ede8)

# EX-NOR:
# program:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/a0dd80a5-6ead-4cbc-9fe5-1965a83946a9)

# Logic symbol & Truthtable:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/f707a5bf-2664-416a-b4f8-57baa2ee4de6)

# RTL:
![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/635b9fbc-62f5-4160-b4d9-4e038d4ec5e0)

# RTL realization Output:
 ![image](https://github.com/sanjevrm/study-of-basic-gates/assets/155142423/9c0094e0-2963-4e2f-9547-4f8a7c5b6f3a)

# Result:
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified

