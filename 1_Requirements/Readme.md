# Requirements
## Introduction
In the era of automation, every individual is looking for comfort and advanced technologies.In many countries there is a vast need of heating system in vehicles due to low temp outside.In this project the automated heating system the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. The Heater will generate the heat and a LCD display will show requested the temperature. In our project we have used ATmega328 microcontroller along with temperature sensor, Push button, Heat generator, LED and LCD diplay,etc.
## Features
- The Sensor will sense wether any person is inside the vehicle or not.
- Tempeature can be controlled manually
- It is best for countries with low temperature
- Low cost and robust system.
## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Easy to alter the temperature inside the vehicles.
- Modular Approach
- Low cost and Robust system.
### Weakness
- Its only applicable for those countries which are having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.
## 4W's and 1'H
### **WHAT** : Automated seat heating with use of sensors
### **WHERE** : Broadly used in automobile Industries
### **WHEN** : Temperature is low
### **WHY** : Health issues
### **HOW** : Heat generating with help of embedded systems

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1      | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   | Thermoelectric module|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |
