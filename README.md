
# Implementation-of-Half-subtractor-and-Full-subtractor-circuit

# AIM:

To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

 Hardware – PCs, Cyclone II , USB flasher, Software – Quartus prime

 
# Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.


# Half Subtractor Full Subtractor:

## Half Subtractor:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

# Procedure

STEP 1: Use module project name(input,output) to start the Verilog programmming.

STEP 2: Assign inputs and outputs using the word input and output respectively.

STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

STEP 4: Use each output to represnt onre for differnce and the other for borrow.

STEP 5: End the verilog program using keyword endmodule. 


# Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.


Developed by:  MERCY A

RegisterNumber:  23012506
*/
### Half Subtractor:

![HS code](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/3f91aa68-96e0-48f2-81a1-9b1f044ddd7a)

### Full Subtractor:

![FS code](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/02975fce-d747-43f9-b0ec-90739644e13d)


# Logic diagram:

### Half Subtractor:

![HS diagram](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/466b46af-5510-4252-90ea-1dbe228c5376)


### Full Subtractor:

![FS diagram](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/d7d692ac-7219-4e15-a37c-2779284bf059)


# Output:

### HALF SUBTRACTOR:

![image](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/1301c277-2f49-4da8-bb88-450bdfa22b0b)

### FULL SUBTRACTOR:

![image](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/c9212ddf-83b8-46de-b8bd-490a3386f131)



# Truthtable:

### Half Subtractor:

![image](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/c87e32c4-73cd-4d03-a99e-22cf0b063445)

### Full Subtractor:

![image](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/e4fe2cf3-3acc-4fa6-9705-a9d8ac208989)


# Timing diagram:

### Half Subtractor:

![HS wave](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/a3fff71d-efc5-46f3-92a4-f958608f9011)

### Full Subtractor:

![FS wave](https://github.com/mercyarulappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149233730/20de288c-dede-4b0b-9f57-446ab528c8cb)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
