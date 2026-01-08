# Flip-Flops and Sequential Circuits

## Overview
This project explores the design, simulation, and hardware implementation of fundamental **sequential logic circuits** using flip-flops. The work was completed as part of Electrical Engineering Laboratory II and focuses on understanding memory elements, clocked behavior, and timing in digital systems.

The project includes the design and testing of:
- D-type latches
- Synchronous and asynchronous (ripple) counters
- Shift registers

Each circuit was first verified through simulation and then implemented on a breadboard using TTL integrated circuits.

---

## Objectives
- Analyze the behavior of flip-flops and latches
- Compare synchronous and ripple counter architectures
- Implement counters and shift registers using ICs
- Validate theoretical operation through hardware measurements
- Observe timing, propagation delay, and clocked behavior

---

## Implemented Circuits

### D-Type Latch
- Verified level-sensitive operation
- Observed that output follows input only when clock is high
- Confirmed correct timing behavior using a logic analyzer

### 3-Bit Modulo-8 Synchronous Counter
- Built using JK flip-flops and logic gates
- All flip-flops clocked simultaneously
- Demonstrated clean state transitions and predictable timing

### 3-Bit Modulo-8 Ripple Counter
- Constructed using D flip-flops
- Each stage clocked by the previous output
- Observed propagation delay between stages

### 4-Bit Shift Register
- Implemented with D flip-flops sharing a common clock
- Demonstrated sequential data movement across stages
- Verified operation using oscilloscope and logic analyzer

---

## Tools and Equipment
- Multisim (circuit simulation)
- Breadboard (protoboard)
- Oscilloscope
- Logic Analyzer
- Word / Logic Generator
- TTL ICs (74LS74, 74LS76, 74LS00)
- Triple DC Power Supply

---

## Results and Observations
- Hardware behavior closely matched Multisim simulations
- Synchronous counters exhibited better timing performance than ripple counters
- Ripple counters showed expected propagation delays
- Shift register data movement was clearly visible on timing traces
- Minor noise was occasionally observed due to breadboard wiring

---

## Key Concepts Demonstrated
- Sequential logic design
- Clocked digital systems
- Timing and propagation delay
- Flip-flop based memory elements
- Practical digital hardware debugging

---

## Documentation
- Full lab report (PDF)
- Simulation schematics
- Oscilloscope and logic analyzer captures
- Breadboard implementation photos

---

## Notes
This project emphasizes **hardware validation of digital logic concepts**, bridging theoretical design with real-world electrical behavior.
