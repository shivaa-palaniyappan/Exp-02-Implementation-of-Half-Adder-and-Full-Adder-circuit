# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime Theory Adders are digital circuits that carry out addition of numbers.

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

Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.
### Program:

Developed by: SHIVAA PALANIYAPPAN V
RegisterNumber:  23007210

## CODE :
## HALF ADDER :
![Exp3 ha code](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/4bcc8a4f-51aa-4715-bede-7d48987cdbad)
## FULL ADDER :
![Exp3 fa code](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/f765620c-3696-4a6b-a548-2c06343c136d)

## TRUTH TABLE :
## HALF ADDER :
![Exp3 truthtable (ha)](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/85378b71-881a-40fa-840e-37294c34d563)
## FULL ADDER :
![Exp3 truthtable (fa)](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/44342f2f-7394-49db-a910-8b8ba8fb8ada)

Logic symbol & Truthtable
RTL realization

### Output:

### RTL :

## HALF ADDER :
![Exp3 ha RTL diagram](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/8c14fcf5-780a-4ff7-a229-f53a95ba2cbe)
## FULL ADDER :
![Exp3 fa RTL diagram](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/113c3105-5359-4b80-8a51-0ef7fe8d7585)

### TIMING DIAGRAM :
## HALF ADDER :
![exp3 ha wave](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/0e87e2dc-c095-4eb2-93fb-142a6f15c70b)
## FULL ADDER :
![exp 3 fa wave](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/2aa2281e-fed4-41cf-8289-dd3baa799924)


### TRUTH TABLE :

## HALF ADDER :
![Exp3 truthtable (ha)](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/c722c22b-e67d-4430-ae09-84c7a770e3f6)
## FULL ADDER :
![Exp3 truthtable (fa)](https://github.com/shivaa-palaniyappan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146915611/4e9caee7-daac-47d2-8696-8c0f69144382)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming.
