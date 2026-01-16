# Audio Amplifier and Microphone System

## Overview
This project focuses on the design, simulation, and hardware implementation of a discrete analog audio amplification system. The work was completed in multiple parts, progressing from a small signal voltage amplifier to a power amplifier capable of driving a speaker, and finally integrating a microphone input for real audio capture and playback.

All amplifier stages were first analyzed theoretically, verified through Multisim simulation, and then constructed and tested on a protoboard using discrete components.

## Implemented Stages
- Single stage common emitter voltage amplifier (audio preamplifier)
- Class B push pull power amplifier
- Microphone signal integration into the amplifier chain

## Objectives
- Design and bias a BJT based audio voltage amplifier  
- Analyze gain, input/output impedance, and frequency response  
- Implement a power efficient output stage capable of driving an 8 Ω load  
- Measure amplifier performance using lab instrumentation  
- Integrate a microphone level signal into the amplifier system  
- Observe real world effects such as distortion, efficiency, and noise  

## Circuit Highlights

### Common Emitter Voltage Amplifier (Preamp)
- Designed for mid band voltage gain suitable for audio signals  
- Biasing network selected to ensure stable operation in the active region  
- Input and output coupling capacitors used to block DC offsets  
- Measured gain closely matched simulation and theoretical predictions  
- Frequency response demonstrated expected low frequency roll off behavior  

### Class B Push Pull Power Amplifier
- Implemented to efficiently deliver power to an 8 Ω speaker  
- Push pull topology selected to improve efficiency over class A operation  
- Achieved output power exceeding the design requirement  
- Measured efficiency surpassed 40%, meeting project specifications  
- Output waveforms confirmed proper amplification with manageable distortion  

### Microphone Integration
- Microphone level signals were successfully interfaced with the amplifier system  
- AC coupling was used to prevent DC bias interference between stages  
- The amplifier chain provided sufficient gain to amplify microphone input to an audible output  
- The complete system demonstrated microphone to speaker functionality  
- Measurement data was collected for the microphone stage and will be documented in a dedicated report  

## Results and Observations
- Experimental measurements closely matched Multisim simulations  
- Bias voltages remained stable across operating conditions  
- The voltage amplifier provided consistent mid band gain  
- The power amplifier delivered sufficient output power with good efficiency  
- Microphone input was successfully amplified and reproduced through the speaker  
- Minor noise and distortion were observed, primarily due to breadboard wiring and component tolerances  

## Tools and Equipment
- Multisim (circuit simulation)  
- Protoboard (breadboard implementation)  
- Oscilloscope  
- Function generator  
- DC power supply  
- Discrete BJTs, resistors, capacitors  
- 8 Ω speaker load  

## Key Concepts Demonstrated
- Analog audio amplifier design  
- BJT biasing and small signal analysis  
- Gain staging and signal conditioning  
- Power amplification and efficiency  
- Microphone level signal integration  
- Practical analog hardware debugging  

## Documentation
Complete project documentation with schematics, calculations, simulations, and experimental measurements:
(Project is completed but the report is still in progress)
 
  • Audio Amplifier (Part I) - Project Report (PDF)  
  • Audio Amplifier (Part II) - Project Report (PDF)  
  • Microphone Integration Project Report (PDF)
