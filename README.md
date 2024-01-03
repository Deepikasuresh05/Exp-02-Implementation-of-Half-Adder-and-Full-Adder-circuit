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
 
# Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
~~~
Developed by: S DEEPIKA
~~~
RegisterNumber:  23002257
*/

![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/81702906-1e12-4c9c-968a-c3fe290d3f48)

![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/68cdd9f0-44fb-401c-a454-80da6c755d34)

# Truthtable
# Half Adder
![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/355bb455-6523-4317-9e84-0a863efc8737)
# Full Adder
![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/c1c68354-bb90-4289-bdc5-ab8a12db6ea5)
# RTL realization
![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/571a7993-91e6-4fd4-9e09-bd171a258cd6)
# Output:

![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/eb84676a-ede9-490c-a773-6d01ce28123a)

![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/9c1ecc64-ef75-43e4-bb5e-e23deb9e6ac8)

# RTL
![image](https://github.com/Deepikasuresh05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514509/8ead8e4f-1657-446e-aaaa-6ee8d3cefefe)

### Result:
Thus the Half adder and the Full adder is Verified
