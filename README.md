NAME: RAMYA R

REG NO: 23000505

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
HALF ADDER:
![Screenshot 2023-12-02 144838](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/118e1ca3-2eb6-4c19-9c9b-cb34c4907df1)
FULL ADDER:
![Screenshot 2023-12-02 144849](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/85b61c37-e428-4836-8b0f-6e3b11b455b5)

Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
HALF ADDER:
![Screenshot 2023-12-02 144902](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/dbc8fc5e-30a1-47d1-869c-bdb8e38d8f97)
FULL ADDER:
![Screenshot 2023-12-02 144914](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/443fba95-a3a6-4040-aed0-e59f166c6a4a)

RTL realization
HALF ADDER:
![Screenshot 2023-12-02 144925](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/8cd3ad0c-a0bd-40ed-a515-7baa3901688d)
FULL ADDER:
![Screenshot 2023-12-02 144933](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/d426f442-2fcf-4627-a99a-658c5b2f3a47)

### Output:
### RTL
### TIMING DIAGRAM
HALF ADDER:
![Screenshot 2023-12-02 145049](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/1ff3c054-8304-4a60-b7df-6a2bce2c360f)
FULL ADDER:
![Screenshot 2023-12-02 145100](https://github.com/ramya23000505/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149370791/73b5c4c3-78fd-4a3e-aab2-75db105a386f)



### TRUTH TABLE 

### Result:
