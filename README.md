# Experiment--04-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
### Hardware – PCs, Cyclone II , USB flasher
### Software – Quartus prime
## Theory:
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

### Half Subtractor Full Subtractor
### Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

### Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure:




## Program:
### Half Subtractor
![CODE_HSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/6ada5e89-8910-45c4-ab72-04b41fbc72f1)

### Full Subtractor
![CODE_FSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/aeea4908-1247-4a97-b5e9-a4912e7b8e9d)

## Output:

## Truthtable
### Half Subtractor
![TT_HSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/787b921d-a5b7-4019-aff1-f5bbb91d51b5)

### Full Subtractor
![TT_FSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/f2e3074d-3ba6-4b8a-92ec-5c70de5c9ae6)

##  RTL realization
### Half Subtractor
![RTL_HSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/f75aec53-ec44-4f13-a475-3ba7210e68f9)

### Full Subtractor
![RTL_FSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/ad0d9ec2-81e6-42a8-b543-63b7fd432365)

## Timing diagram 
### Half Subtractor
![TIMING_HSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/c532229f-26b6-4800-b5e1-2da9720962ea)

### Full Subtractor
![TIMING_FSUB](https://github.com/MOHAMEDAHSAN/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139331378/9f106e26-efc6-4e4a-a5a1-a1aab4da613d)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
