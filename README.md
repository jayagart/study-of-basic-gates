## NAME: jayagar.T
## REG NO: 24901219
# EXPERIMENT 1 - Study of basic gates

# AIM

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

# EQUIPMENT REQUIRED

Software – Quartus prime 

# THEORY

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

OR gate

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

# PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM

### Program for logic gates and verify its truth table in quartus using Verilog programming
### module logicgates(a,b,notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate);
### input a,b;
### output notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate;
### not(notgate,a);
### and(andgate,a,b);
### or(orgate,a,b);
### nand(nandgate,a,b);
### nor(norgate,a,b);
### xor(xorgate,a,b);
### xnor(xnorgate,a,b);
### endmodule

 
 
# LOGIC SYMBOL AND TRUTH TABLE
![WhatsApp Image 2024-10-23 at 22 45 04_60cedc7f](https://github.com/user-attachments/assets/180dab2f-3d28-4f06-9f99-8bf07a464d53)


# RTL OUTPUT
![Screenshot 2024-10-24 144438](https://github.com/user-attachments/assets/917665ec-0f26-4072-a5a6-935b1022d164)




# OUTPUT WAVEFORM
![Screenshot 2024-10-24 144759](https://github.com/user-attachments/assets/cb82a4b5-590a-4d44-94be-fa978ec2e6e8)



# RESULT

 Studied and verified the truth table of logic gates in Quartus II using Verilog programming,verified successfully.


