# Baset's Motor

Contains Jupyter Notebook and overlay allowing control of the Linear Stepper Motor using AXI GPIO
Also contains Interrupt support

- Pinout for PMOD testing:
- | 3.3v GND P4 P3 P2 P1 |
- | 3.3v GND P8 P7 P6 P5 |

- Pin 1: Encoder A
- Pin 2: Encoder B
- NC if not listed

## Block Diagram of Design:

<img src="https://github.com/AVHBAC/main/blob/BasetMotor/Images/MainBlockDiagram.PNG">

## Interrupt Controller Settings:

<img src="https://github.com/AVHBAC/main/blob/BasetMotor/Images/AxiIntc.PNG">

### Note: there is Uart AXI component in this because I forgot to remove it but it is not used
