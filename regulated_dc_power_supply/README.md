# Regulated DC Power Supply

## Overview

This project focuses on the design, simulation, and analysis of a regulated DC power supply capable of delivering a stable output voltage under varying load conditions. The system was developed to demonstrate the limitations of unregulated supplies and the improvements achieved through voltage regulation using a Zener reference and operational amplifier feedback.

The power supply was designed and evaluated using Multisim simulation and verified through breadboard implementation and oscilloscope measurements.

## Implemented Circuits

• Unregulated DC power supply (transformer, bridge rectifier, capacitor filter)  
• Zener diode voltage reference  
• Op-amp based voltage regulator  
• Regulated 6 V and 12 V DC outputs  

## Objectives

• Design a DC power supply with regulated output voltage  
• Analyze load regulation and ripple voltage under varying loads  
• Compare unregulated and regulated power supply behavior  
• Verify voltage stability using simulation and hardware measurements  
• Evaluate regulator performance at light and heavy load conditions  

## Circuit Highlights

### Unregulated Power Supply

The unregulated supply consists of a step down transformer, full wave bridge rectifier, and capacitor filter. While the capacitor reduced ripple, the output voltage varied significantly with load changes, demonstrating poor load regulation and increased ripple at higher currents.

### Zener Voltage Reference

A Zener diode reference circuit was used to generate a stable reference voltage. A series resistor ensured proper Zener current, maintaining operation in the breakdown region and providing a reliable reference for regulation.

### Op-Amp Voltage Regulator

An operational amplifier was used to regulate the output voltage by comparing the output to the Zener reference through a feedback network. Proper resistor selection allowed the output voltage to be set to desired levels while improving regulation and reducing ripple.

### Regulated DC Output (6 V and 12 V)

The regulated supply maintained stable 6 V and 12 V outputs across load currents up to 200 mA. Load regulation remained below 1%, and ripple voltage stayed within acceptable limits, confirming effective regulation.

## Results and Observations

The unregulated supply exhibited significant voltage drop and increased ripple under load. In contrast, the regulated supply maintained stable output voltages with minimal ripple across varying load conditions. Measured load regulation was approximately 0.5% for the 6 V output and 0.75% for the 12 V output, demonstrating strong voltage stability and effective regulation.

## Tools and Equipment

• Multisim (circuit simulation)  
• Breadboard (protoboard)  
• Oscilloscope  
• DC power supply  
• Function generator  
• Digital multimeter  
• Operational amplifier  
• Zener diode and discrete components  

## Key Concepts Demonstrated

• AC to DC power conversion  
• Voltage regulation techniques  
• Load regulation and ripple analysis  
• Zener diode reference circuits  
• Op-amp feedback control  
• Power supply performance evaluation  

## Documentation

Full project report with schematics, simulations, measurements, and analysis:

• Regulated DC Power Supply Project Report (PDF)
