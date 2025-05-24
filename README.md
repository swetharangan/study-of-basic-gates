### EX-1 <p align="center"><b>IMPLEMENTATION OF BASIC LOGIC GATES    </b>   

**DATE:24/5/2025**

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electro Circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
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
Developed by: R.swetha 
RegisterNumber: 212223040221

## AND GATE 

**PROGRAM**

![Screenshot 2024-04-10 142913](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/a8e0cd25-1b76-4d49-bcbd-e6db480f1636)

**Logic symbol & Truthtable**

![319458613-e333ab21-f7bf-4aa0-8a6b-f69c57451122](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/2b5d8051-685d-4c4a-9d6c-801fb32699ec)

**RTL:** 

![Screenshot 2024-04-10 142943](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/c079cb96-219d-4bbf-becf-d64dbca0a257)

**RTL realization Output**

![Screenshot 2024-04-10 142822](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/27f19c72-48e4-4ad8-bb28-0fc9aee4df76)

## OR GATE

**PROGRAM**

![Screenshot 2024-04-10 144038](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/7d1e6de3-f784-4367-89c3-05ee1bdff7cc)

**Logic symbol & Truthtable**

![319458650-7c6f142b-46a3-4e36-a4c7-76008d1b9832](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/374a911e-70ec-42b1-b190-a20669f539da)

**RTL:** 

![Screenshot 2024-04-10 144052](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/65d24ccf-ec36-4f93-baea-b02aab4878e7)

**RTL realization Output**

![Screenshot 2024-04-10 144504](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/09f04f41-781b-4b03-81d8-be475b7181c5)

## NOT GATE

**PROGRAM**

![Screenshot 2024-04-10 204936](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/cb86e1ce-5f4e-4e5f-ad03-b56c304e44c3)

**Logic symbol & Truthtable**

![319459057-19d8cb59-7eab-4f7b-a45d-296947b83146](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/10bea093-64d3-4b90-aecf-e83971840dcb)

**RTL:** 

![Screenshot 2024-04-10 204959](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/dd3b3569-c103-42fd-965d-e3c7eb0f3578)

**RTL realization Output**

![Screenshot 2024-04-10 205151](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/b7ba3b58-8207-4ebd-9d2e-81289708d01e)

## NAND GATE

**PROGRAM**

![Screenshot 2024-04-10 213505](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/d5820b88-c3df-4521-a6aa-78cc5a2f3146)

**Logic symbol & Truthtable**

![319458770-a0137613-8911-48f3-b17b-8f2829320975](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/3ebe517f-edf4-49fc-b51d-8caf4735f991)

**RTL:** 

![Screenshot 2024-04-10 213528](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/76351623-5401-4696-bd5a-9a82196dd4b2)

**RTL realization Output**

![Screenshot 2024-04-10 213702](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/b4657d61-b2de-4023-ad6c-66eabd545ac1)

## NOR GATE

**PROGRAM**

![Screenshot 2024-04-10 210719](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/fae9e945-2095-4314-8ec3-a0d51fa6b930)

**Logic symbol & Truthtable**

![319458802-eb93295d-0d69-4b8f-bedd-99ec4f99c4aa](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/0d929c8e-6dc2-4e64-9c02-3312e0b2f93b)

**RTL:** 

![Screenshot 2024-04-10 210802](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/904cdba9-adb5-4d9b-81c8-4ddc9773164f)

**RTL realization Output**

![Screenshot 2024-04-10 210946](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/19bae2d8-1d65-41fc-ae56-4bb2a584ac1c)

## EX-OR GATE

**PROGRAM**
![Screenshot 2024-04-10 210033](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/fb46f1fa-9c95-4fbd-95b2-3e3c45820579)


**Logic symbol & Truthtable**

![319458857-dfcd8129-dc9c-47bf-9dc1-8d34142f0f81](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/0004fb3e-04b9-4576-aae0-f15c0892aded)

**RTL:** 

![Screenshot 2024-04-10 210055](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/2464a092-baac-4f0f-b513-c9215716c623)

**RTL realization Output**

![Screenshot 2024-04-10 210237](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/5072be06-9491-4add-a231-2285bd549eca)

## EX-NOR GATE

**PROGRAM**

![Screenshot 2024-04-10 211635](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/e2b3c19d-6c68-457e-ae55-f5fa37438d3f)

**Logic symbol & Truthtable**

![319458896-ed25b34e-8a78-4fd1-9b9b-86894a498f7d](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/0bba7e42-3241-476d-ba93-1d1d6cd11e43)

**RTL:** 

![Screenshot 2024-04-10 211652](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/910f92f7-781d-4b92-96e2-a1f4cb0d5c1f)

**RTL realization Output**

![Screenshot 2024-04-10 212754](https://github.com/Jesubalan19/study-of-basic-gates/assets/144979294/345d88d1-fb23-4819-9540-65c94354d274)

**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.

