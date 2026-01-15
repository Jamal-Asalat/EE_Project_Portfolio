Diodes and Diode Circuits
Overview

This project examines the behavior and practical applications of diodes through circuit simulation and hands-on laboratory measurements. The work includes characterization of diode I–V behavior, implementation of rectifier circuits, development of a filtered DC power supply, and analysis of Zener diode voltage regulation.

The objective was to understand how diode physics translates into real-world power electronics and signal conversion circuits.

Key Topics Covered

• Diode I–V characteristics in forward and reverse bias
• Half-wave rectification
• Full-wave bridge rectification
• Capacitor-based filtering for DC power supplies
• Zener diode operation and voltage regulation
• Comparison of simulation results with experimental measurements

Experiments Performed
Diode I–V Characteristics

DC voltage and current sweeps were performed using simulation and physical measurements. The exponential I–V behavior was observed, and the diode knee voltage was identified in the 0.6–0.7 V range. Experimental results were compared to ideal diode and battery models.

Half-Wave Rectifier

A half-wave rectifier was constructed using a single diode and resistive load. A sinusoidal AC input produced a pulsating DC output, verified using oscilloscope measurements.

Full-Wave Rectifier

A bridge rectifier using four diodes was implemented to convert both halves of the AC waveform. Voltage drops across conduction paths were measured and matched expected theoretical behavior.

Filtered DC Power Supply

A capacitor filter was added to the full-wave rectifier to reduce output ripple and produce a smoother DC voltage. Measured ripple closely matched theoretical calculations.

Zener Diode Characteristics

Forward and reverse I–V behavior of a Zener diode was analyzed. Reverse breakdown was observed near the specified Zener voltage and confirmed through both simulation and lab measurements.

Zener Voltage Regulation

A Zener-based regulation circuit was implemented and tested under varying load conditions. Regulation limits were identified based on Zener current requirements.

Tools and Equipment

• Oscilloscope
• Function generator
• DC power supply
• Digital multimeter (DMM)
• Breadboard (protoboard)
• MATLAB
• Multisim

Results and Observations

Experimental results closely matched simulation data across all circuits. Diode knee voltage and rectifier behavior aligned with theory, capacitor filtering significantly reduced ripple voltage, and the Zener diode maintained a stable output voltage within its operating current range. Minor discrepancies were attributed to component tolerances and measurement limitations.

Documentation

• Full laboratory report (PDF)
• Circuit schematics
• Oscilloscope waveforms
• MATLAB plots

Skills Demonstrated

• Power electronics fundamentals
• Circuit analysis and troubleshooting
• Laboratory measurement techniques
• Simulation-to-hardware validation
• Technical documentation and reporting
