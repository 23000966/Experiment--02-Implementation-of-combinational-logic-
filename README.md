# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:


 Hardware – PCs, Cyclone II , USB flasher Software – Quartus prime


## Theory
Logic gates are electronic circuits which perform logical functions on one or more inputs to produce one output.

OR Gate: The OR gate is a fundamental digital logic gate that operates on two binary inputs, producing an output of 1 if at least one input is 1. It symbolizes logical disjunction and is essential in building logical circuits and decision-making processes in computers and electronics.

AND Gate: The AND gate is a fundamental digital logic gate with two inputs and one output. It produces a high output (1) only when both input signals are high (1). If any input is low (0), the output remains low. It's a building block for more complex logic circuits and is integral in digital computations.

NOT Gate: The NOT gate is a fundamental digital logic gate. It has a single input and a single output. The output is the inverse of the input: if the input is high (1), the output is low (0), and vice versa. It's a basic building block in digital circuits, used for logic inversion. 

## Procedure
1.Create a project with required entities.

2.Create a module along with respective file name.

3.Run the respective programs for the given boolean equations.

4.Run the module and get the respective RTL outputs.

5.Create university program(VWF) for getting timing diagram.

6.Give the respective inputs for timing diagram and obtain the results.
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: SANTHOSH KUMAR R
RegisterNumber: 23000966
![image](https://github.com/23000966/Experiment--02-Implementation-of-combinational-logic-/assets/153983364/706baa89-c55f-4ae3-a151-407a7f657df5)
*/
## RTL realization
![image](https://github.com/23000966/Experiment--02-Implementation-of-combinational-logic-/assets/153983364/7daafa15-5f22-4e9c-a685-eefe88914382)
![image](https://github.com/23000966/Experiment--02-Implementation-of-combinational-logic-/assets/153983364/6b786c30-e3e1-4ee9-b04b-c6f93d3d9d04)

## Timing diagram:
![image](https://github.com/23000966/Experiment--02-Implementation-of-combinational-logic-/assets/153983364/84b9d452-8007-4bcb-8870-fa789fc8e3f7)

## Truth table
![image](https://github.com/23000966/Experiment--02-Implementation-of-combinational-logic-/assets/153983364/3493f081-a7de-44c0-9e0e-e5e8fdfa10b9)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
