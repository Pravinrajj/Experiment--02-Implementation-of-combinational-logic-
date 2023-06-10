# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
STEP 1:
Create a project with required entities.

STEP 2:
Create a module along with respective file name.

STEP 3:
Run the respective programs for the given boolean equations.

STEP 4:
Run the module and get the respective RTL outputs.

STEP 5:
Create university program(VWF) for getting timing diagram.

STEP 6:
Give the respective inputs for timing diagram and obtain the results.
## Program:
```
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: Pravinrajj
RegisterNumber:  212222240080

module expf1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & d) | (~a & b & d) | (a & b &~c));
endmodule

module exp2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((x & y) | (~y & z) | (w & y));
endmodule 
*/
```
## RTL realization and output
![233419128-0811f8be-225e-4d5f-a2c6-fa57e4b5fa24](https://github.com/Pravinrajj/Experiment--02-Implementation-of-combinational-logic-/assets/117917674/c2aba95f-98b7-48c1-9ad3-58b86864f632)
![233417345-1a7e715d-42ba-4cf3-b0ce-891063b6a06e](https://github.com/Pravinrajj/Experiment--02-Implementation-of-combinational-logic-/assets/117917674/e6929884-f614-4006-9bef-12e37492c9b8)

## Timing Diagram
![233417783-24ec1b9d-28f6-4768-9935-848462aa091f](https://github.com/Pravinrajj/Experiment--02-Implementation-of-combinational-logic-/assets/117917674/606fa447-d08a-491d-a52b-99816b2520df)
![233417917-ac2d39ba-fc52-492b-82e6-f8877c012136](https://github.com/Pravinrajj/Experiment--02-Implementation-of-combinational-logic-/assets/117917674/d62478ae-cd52-4e56-8377-ef97f2c84532)

## Truth Table
![233418234-8d70d002-01b7-4bb2-85f1-c0798d99e5aa](https://github.com/Pravinrajj/Experiment--02-Implementation-of-combinational-logic-/assets/117917674/a2ed27a3-bf41-4686-ae83-ba85d8e25a7d)
![233419454-5168c36f-8c56-4f91-96e5-361f61f9a3a4](https://github.com/Pravinrajj/Experiment--02-Implementation-of-combinational-logic-/assets/117917674/85352a9c-c465-4c16-ae18-8c1df9f112e3)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
