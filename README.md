# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: KIRANBALAGI H

RegisterNumber:  23002730

Code:

Half adder:

![Exp3 ha code](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/bf1b2728-b19f-44d8-bede-3f54cd85770d)

Full Adder:

![Exp3 fa code](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/482898dc-4c7a-4785-ad44-1a5b5b0f3f83)

RTL Diagram:

Half adder:

![Exp3 ha RTL diagram](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/a9743254-a0ac-4f0e-b416-e2863852edca)

Full adder:

![Exp3 fa RTL diagram](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/1d64e90c-8a11-4a6c-9262-9ee2ec5a4ba4)

Truth table:

Half adder:

![Exp3 truthtable (ha)](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/81d5f9c8-6f8b-45eb-abb1-f3778f380f80)

Full adder:

![Exp3 truthtable (fa)](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/356ec84f-e1f4-4bb4-a20f-74c9aa7561db)

Output:

Half adder:

![Exp2 wave](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/b4160a13-d931-4583-9f12-029ef95b070a)

Full adder:

![Exp3 fa wave](https://github.com/KiranbalajiH/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149135475/56636adc-a8fc-4d9a-b99c-5294754ddd57)


### Result:

 Thus the half adder and full adder circuit are designed and the truth table for half adder and full
 adder are verified
