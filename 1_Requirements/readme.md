## Requirements

#### Introduction

Stepper motor is a brushless DC motor that divides the full rotation angle of 360° into a number of equal steps. The motor is rotated by applying a certain sequence of control signals. The speed of rotation can be changed by changing the rate at which the control signals are applied. Various stepper motors with different step angles and torque ratings are available in the market. A microcontroller can be used to apply different control signals to the motor to make it rotate according to the need of the application.

Here we are going to interface 6 wires Unipolar Stepper Motor with ATmega32 controller.
Only four wires are required to control the stepper motor. 
Two common wires of stepper motor connected to 5V supply.
ULN2003 driver is used to the driving stepper motor.
Note that to know winding coil and their center tap leads measure resistance in between leads. From center leads, we will get half the resistance value of that winding.
