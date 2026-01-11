# ISXMPL3715ex2

# Example: Using the IS3715 I2C DMX Controller with Arduino IDE

## Objective
Demonstrate how to write a program for the **IS3715 I2C DMX Controller** using the **Arduino IDE**.

## Required Material
- **Kappa3715Ard Board** (INACKS evaluation board featuring the IS3715)  
- **Arduino UNO Board**  
- **DMX-compatible light fixture**  

## Setup
1. Flash the Arduino UNO with the provided code.  
2. Connect the Kappa3715 to the Arduino UNO.  
3. Attach a DMX light to validate its operation.  

## How it works
The Arduino code reads the IS3710 memory map registers 1, 2, and 3, which correspond to DMX channels 1, 2, and 3.  
It then maps these values to the PWM outputs on pins 9, 10, and 11.  
As a result, controlling these three DMX channels with a DMX controller will change the color of the RGB LED.

## Other
- Buy the Kappa3710Ard board and download its documentation: [Kappa3710Ard Documentation](https://inacks.com/kappa3710ard)
- Buy the IS3710 chip and download its documentation: [IS3710 Documentation](https://inacks.com/is3710)

