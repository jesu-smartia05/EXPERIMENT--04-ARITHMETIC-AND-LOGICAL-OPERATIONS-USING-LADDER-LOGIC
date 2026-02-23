# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
# NAME: Jesu Smartia A
# REGISTER NUMBER: 212223110016
# DEPARTMENT: B.E.CSE(IOT)
# YEAR: III
# DATE: 23.02.2026
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
<img width="1919" height="930" alt="Screenshot 2026-02-23 105533" src="https://github.com/user-attachments/assets/1fea9742-601e-44a8-8cb3-019a99f7e46f" />

<img width="1918" height="896" alt="Screenshot 2026-02-23 105547" src="https://github.com/user-attachments/assets/a3947f1b-0773-4909-9704-65c2c97d6298" />

<img width="1910" height="431" alt="Screenshot 2026-02-23 105610" src="https://github.com/user-attachments/assets/b81b41b6-cd7a-4b2d-be7f-d2791eae61d6" />

##  Simulation Screenshots:
## ADDITION:
<img width="1919" height="888" alt="Screenshot 2026-02-23 104756" src="https://github.com/user-attachments/assets/aff49907-a92d-4508-87b9-9be9e5032a8c" />

## SUBTRACTION:
<img width="1918" height="874" alt="Screenshot 2026-02-23 104814" src="https://github.com/user-attachments/assets/7f1f91d0-b0a1-4db8-b03e-945d7b0a1c51" />

## MULTIPLY:
<img width="1919" height="888" alt="Screenshot 2026-02-23 104830" src="https://github.com/user-attachments/assets/bb80b95c-08e7-465e-a938-7660faa92e70" />

## DIVISION:
<img width="1919" height="889" alt="Screenshot 2026-02-23 104846" src="https://github.com/user-attachments/assets/e7d15cd3-7689-4a28-8676-385437dcce6e" />

## OR:
<img width="1912" height="847" alt="Screenshot 2026-02-23 104859" src="https://github.com/user-attachments/assets/42062eb1-a15f-43d8-a7cb-bc3d60bbb3f6" />

## AND:
<img width="1905" height="895" alt="Screenshot 2026-02-23 104914" src="https://github.com/user-attachments/assets/1cbc2185-7624-43b9-95e7-ab0c20135ef5" />

## XOR:
<img width="1919" height="888" alt="Screenshot 2026-02-23 104930" src="https://github.com/user-attachments/assets/cafa8a22-a86d-49e5-9905-dab3567ed6e0" />

## NEGATIVE(NOT):
<img width="1902" height="887" alt="Screenshot 2026-02-23 104943" src="https://github.com/user-attachments/assets/78ad1684-9d65-410a-b2f7-a993137f8308" />

## DECREMENT:
<img width="1915" height="875" alt="Screenshot 2026-02-23 104955" src="https://github.com/user-attachments/assets/560e0eac-ff3e-4a3b-a182-d78fb173fb01" />

## INCREMENT:
<img width="1919" height="878" alt="Screenshot 2026-02-23 105009" src="https://github.com/user-attachments/assets/9611db0e-4945-4f60-9d91-98be02faed8a" />

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
