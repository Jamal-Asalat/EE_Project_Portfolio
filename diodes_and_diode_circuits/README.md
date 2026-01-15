# Diodes and Diode Circuits

## **Overview**

This project examines the behavior and practical applications of diodes through circuit simulation and hands on laboratory measurements. The work includes characterization of diode I–V behavior, implementation of rectifier circuits, development of a filtered DC power supply, and analysis of Zener diode voltage regulation.

The objective was to understand how diode physics translates into real world power electronics and signal conversion circuits.

## **Implemented Circuits**

• Diode I–V characteristic test circuit  
• Half-wave rectifier  
• Full-wave bridge rectifier  
• Filtered DC power supply  
• Zener diode voltage regulator  

## **Objectives**

• Analyze diode behavior in forward and reverse bias  
• Implement and evaluate half-wave and full-wave rectifier circuits  
• Design a filtered DC power supply using capacitor smoothing  
• Examine Zener diode operation and voltage regulation  
• Compare simulation results with experimental measurements  

## **Circuit Highlights**

### **Diode I–V Characteristics**

DC voltage and current sweeps were performed using simulation and physical measurements. The exponential I–V behavior was observed, and the diode knee voltage was identified in the 0.6–0.7 V range. Experimental results were compared to ideal diode and battery models.

### **Half-Wave Rectifier**

A half-wave rectifier was constructed using a single diode and resistive load. A sinusoidal AC input produced a pulsating DC output, verified using oscilloscope measurements.

### **Full-Wave Rectifier**

A bridge rectifier using four diodes was implemented to convert both halves of the AC waveform. Voltage drops across conduction paths were measured and matched expected theoretical behavior.

### **Filtered DC Power Supply**

A capacitor filter was added to the full-wave rectifier to reduce output ripple and produce a smoother DC voltage. Measured ripple closely matched theoretical calculations.

### **Zener Diode Characteristics**

Forward and reverse I–V behavior of a Zener diode was analyzed. Reverse breakdown was observed near the specified Zener voltage and confirmed through both simulation and laboratory measurements.

### **Zener Voltage Regulation**

A Zener-based regulation circuit was implemented and tested under varying load conditions. Regulation limits were identified based on Zener current requirements.

## **Results and Observations**

Experimental results closely matched simulation data across all circuits. Diode knee voltage and rectifier behavior aligned with theory, capacitor filtering significantly reduced ripple voltage, and the Zener diode maintained a stable output voltage within its operating current range. Minor discrepancies were attributed to component tolerances and measurement limitations.

## **Tools and Equipment**

• Oscilloscope  
• Function generator  
• DC power supply  
• Digital multimeter (DMM)  
• Breadboard (protoboard)  
• MATLAB  
• Multisim  

## **Key Concepts Demonstrated**

• Power electronics fundamentals  
• Circuit analysis and troubleshooting  
• Laboratory measurement techniques  
• Simulation to hardware validation  
• Technical documentation and reporting  

## **Documentation**

Full project report with schematics, measurements, and analysis:

• Diodes and Diode Circuits Project Report (PDF)
