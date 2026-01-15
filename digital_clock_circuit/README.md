# Digital Clock Circuit

## Overview

This project focuses on the design, implementation, and testing of a digital clock using discrete digital integrated circuits and seven segment displays. The system was built to generate and display hours, minutes, and seconds using clock pulses, counters, logic gates, and display drivers.

All subsystems were first planned using reference schematics and then implemented on a breadboard while verifying correct timing, counting behavior, and display operation.

## Implemented Circuits

- Seconds counter and display (00–59)
- Minutes counter and display (00–59)
- Hours counter and display (00–23)
- BCD to seven segment display driver stages
- Counter cascading and reset logic
- Clock pulse generation using a function generator

## Objectives

- Design a functional digital clock using small scale integrated circuits
- Implement BCD counting and display decoding
- Cascade counters to represent seconds, minutes, and hours
- Synchronize time units using carry out logic
- Verify timing accuracy using clock pulses
- Display time correctly on seven segment displays

## Circuit Highlights

### Seven Segment Displays and Drivers

Each digit of the clock was driven by a dedicated BCD to seven segment driver IC. The drivers converted BCD outputs from the counters into appropriate segment activation signals, allowing correct numerical display for hours, minutes, and seconds.

### Seconds and Minutes Counters

The seconds and minutes circuits were implemented using BCD counters configured to count from 00 to 59. AND gate logic was used to detect the count of 60 and reset the counters accordingly. The carry out signal from the seconds counter advanced the minutes counter, ensuring proper synchronization.

### Hours Counter

The hours circuit was designed to operate in a 24 hour format using BCD counters and logic gates to reset the count after 23. The hours counter advanced based on the carry out signal from the minutes circuit. Partial operation was achieved, with some instability observed due to wiring complexity.

### Clock Pulse Generation

A function generator provided a square wave clock signal, typically set to 1 Hz, to drive the counters. Adjusting the frequency allowed verification of correct counting behavior and timing relationships across all stages.

## Results and Observations

The seconds, minutes, and hours circuits operated as intended, displaying accurate counts with proper cascading and reset behavior. Display decoding and timing closely matched theoretical expectations, and the clock advanced reliably across all stages. Minor instability encountered during initial testing was resolved through wiring verification and signal integrity improvements. Overall, the system demonstrated correct digital clock operation and emphasized the importance of precise wiring, synchronization logic, and careful hardware implementation in digital systems.

## Tools and Equipment

- Oscilloscope
- Function generator
- DC power supply
- Digital multimeter (DMM)
- Breadboard (protoboard)
- Seven segment displays
- Digital ICs (CD4518, CD4510, CD4543, CD4081)

## Key Concepts Demonstrated

- Digital counting and timing
- Clocked sequential logic
- Counter cascading and reset logic
- BCD encoding and display decoding
- Hardware debugging and signal verification
- Practical implementation of digital systems

## Documentation

Full project report with schematics, measurements, and analysis:

- Digital Clock Cicrcuit Project Report (PDF)
