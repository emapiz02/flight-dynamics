# Fixed-Wing Flight Dynamics Analysis

## Overview
This project focuses on the linear flight dynamics analysis of a fixed-wing aircraft using a state-space approach.
All analyses refer to the same aircraft configuration, for which aerodynamic stability derivatives and trim conditions were provided.

The objective was to study longitudinal and lateral–directional stability, dynamic response to control inputs, and response to atmospheric disturbances.

## Methodology
The aircraft equations of motion were linearized around trimmed equilibrium conditions.
State-space models were developed for both longitudinal and lateral–directional dynamics.

Dynamic characteristics were analyzed through:
- eigenvalue analysis
- frequency-domain analysis
- time-domain simulations

All numerical analyses and simulations were implemented in Python.

## Analyses and Results
The project includes:

### Longitudinal and Lateral–Directional Stability Analysis
- Argand diagrams of longitudinal and lateral–directional modes

### Frequency-Domain Analysis
- Magnitude and phase of transfer functions following elevator deflection

### Time-Domain Response
- Dynamic response to rudder finite-time step input
- Aircraft response and trajectory under step gust input
- Response to stochastic wind input, including power spectral density analysis of angle of attack and load factor

### Stability Augmentation System (SAS)
- Comparison between open-loop aircraft response and aircraft equipped with a Stability Augmentation System under elevator input

## Tools
- Python for numerical modelling and simulations
- State-space analysis and linear algebra
- Time- and frequency-domain analysis

## Code Availability
All code was written by the author in Python. 
Full implementation is not publicly shared, but it can be made available upon request.
Selected results and methodological details are presented for portfolio purposes.
