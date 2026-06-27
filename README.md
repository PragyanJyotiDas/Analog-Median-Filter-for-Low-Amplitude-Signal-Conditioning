# Analog-Median-Filter-for-Low-Amplitude-Signal-Conditioning

## Components Used

This project utilizes a combination of active and passive electronic components to implement the required signal processing functionality.

### Passive Components
- Resistors
- Capacitors
- Inductors

### Active Components
- Operational Amplifiers (Op-Amps)
- Transistors

These components work together to perform analog signal conditioning tasks such as amplification, filtering, and signal control while maintaining low latency and efficient operation.

## Analog Median Filter

This project implements an **analog equivalent of a digital median filter**, designed for real-time noise reduction without digital processing. Unlike conventional digital median filters, the proposed circuit performs filtering entirely in the analog domain, resulting in **zero processing latency**.

### Working Principle
- The input signal is passed through a series of **all-pass filters** to generate **five phase-shifted versions** of the same signal.
- These five signals are processed by the analog median filter circuit, which continuously determines the **median value** among them.
- The median output effectively suppresses impulsive noise while preserving the original signal characteristics.

### Key Features
- Analog implementation of a digital median filter
- Real-time continuous-time operation with **zero latency**
- Effective reduction of impulsive and noisy signal components
- Preserves signal integrity better than conventional linear filters
- Simulated and validated using **LTspice**
