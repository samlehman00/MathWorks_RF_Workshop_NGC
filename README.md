# RF_Workshop_NGC
 MathWorks RF Workshop
# Workshop: Top-Down Design of an RF Receiver and Antenna Front-End Integration

This workshop uses a top-down methodology to design an RF receiver for a 2.4GHz narrowband application. The process includes verifying the error rate performance after adding impairments such as interfering signals and integrating the antenna front-end.

## Overview

### Key Tools:
- **RF Budget Analyzer App (RF Toolbox)** 
- **RF Blockset**
- **Antenna Designer App (Antenna Toolbox)** 
- **RFPCB Toolbox**
- **Communications Toolbox**
  
### IEEE® 802.15.4 System Specifications:
- **Data Rate:** 250kbps
- **Modulation:** OQPSK with half-sine pulse shaping
- **Spread Spectrum:** Direct sequence with chip rate = 2Mchips/s
- **Sensitivity Specification:** -100dBm
- **Bit Error Rate (BER) Specification:** 1e-4
- **ADC Specifications:** 10 bits and 0dBm saturation power

### Receiver Specifications:
- **Noise Figure (NF):** 10.7dB
- **Gain (G):** 51.5dB

## Workshop Exercises

### Exercise 1:
- **Objective:** Starting from the receiver Gain and Noise Figure, design and analyze a cascade of RF components and integrate them into the system-level model.
- **Task:** Measure the corresponding Chip Error Rate (ChER) in the presence of an out-of-band interfering signal.

### Exercise 2:
- **Objective:** Integrate a simple dipole antenna into the system-level model of the RF receiver.
- **Task:** Understand the impact of polarization mismatch.

### Exercise 3:
- **Objective:** Design a dual-polarized antenna, analyze its performance using EM analysis, and integrate it into the system-level model of the RF receiver.
- **Task:** Design a Wilkinson combiner and integrate it together with the dual-polarized antenna into the system-level model.

### Exercise 4:
- **Objective:** Design a 90-degree phase shifter and implement it on a PCB with the Wilkinson combiner.
- **Task:** Analyze the PCB structure using electromagnetic analysis.

## Conclusion

This workshop provides a comprehensive RF receiver and antenna design approach, focusing on practical integration and performance verification. By the end of the workshop, participants will have hands-on experience with system-level modeling, EM analysis, and PCB implementation.


