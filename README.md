# ISXMPL3715ex2

# Example: Using the IS3715 I²C DMX Controller with Arduino IDE

## Objective
Demonstrate how to write a program for the **IS3715 I²C DMX Controller** using the **Arduino IDE**.

## Required Material
- **Kappa3715Ard Board** (INACKS evaluation board featuring the IS3715)  
- **Arduino UNO Board**  
- **DMX-compatible light fixture**  

## Setup
1. Flash the Arduino UNO with the provided code.  
2. Connect the Kappa3715 to the Arduino UNO.  
3. Attach a DMX light to validate its operation.  

## How it works
The Arduino code reads the analog value from the potentiometer on the Kappa3715 board.  
This reading is scaled to a value from **0 to 255**, which corresponds to the valid range for a DMX channel.  
The scaled value is then written to **IS3715 register 1**, which controls **DMX Channel 1**.  

## Other
- Download the example code: [https://inacks.com/is3715](https://inacks.com/is3715)  
- Product information (Kappa3715Ard): [https://inacks.com/kappa3715ard](https://inacks.com/kappa3715ard)

