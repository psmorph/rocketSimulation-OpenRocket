# Two-Stage Rocket Design and Flight Simulation using OpenRocket

## Overview
This project focuses on the design and flight simulation of a model rocket using OpenRocket, with the objective of studying multi-stage propulsion, aerodynamic stability, and flight performance. The project explores key aerospace engineering concepts such as center of gravity (CG), center of pressure (CP), motor configuration, mass distribution, and parachute-based recovery.

## Objectives
- Design and analyze a two-stage rocket configuration.
- Study aerodynamic stability and the relationship between CG and CP.
- Simulate flight performance under configured motor and environmental conditions.
- Investigate the effects of staging on altitude, velocity, and acceleration.
- Understand rocket recovery systems and flight simulation limitations.

## Baseline Simulation Results

The current OpenRocket design provides the following preliminary results:

| Parameter | Simulated Result |
|---|---:|
| Apogee (maximum altitude) | 965 ft (294 m) |
| Maximum velocity | 329 ft/s (100.3 m/s) |
| Maximum Mach number | 0.300 |
| Maximum acceleration | 11.6 G |
| Length | 63.019 in (1.60 m) |
| Maximum body diameter | 3 in (76.2 mm) |
| Mass without motors | 641 g |
| Mass with motors | 728 g |
| Stability margin | 3.52 calibers (16.8%) |
| Center of gravity (CG) | 32.62 in |
| Center of pressure (CP) | 43.188 in |

**Note:** These results correspond to the current baseline configuration shown in OpenRocket, using the displayed G74W-4 motor configuration. They should not be interpreted as results from a completed two-stage flight simulation.

## Tools and Technologies
- **OpenRocket:** Rocket modeling, motor configuration, stability analysis, and flight simulation.
- **Git and GitHub:** Version control and project documentation.

## Future Work
- Complete the booster and sustainer stage configuration.
- Compare single-stage and two-stage flight performance.
- Analyze altitude, velocity, acceleration, and stability across configurations.
- Investigate the influence of payload mass and fin geometry.
- Document simulation plots and compare predictions under different conditions.

## Conclusion
This project provides a practical introduction to model rocket design and aerospace simulation. It establishes a baseline for evaluating aerodynamic stability and predicted flight performance, with further work planned to investigate two-stage propulsion and its effect on overall mission performance.

*Disclaimer: All reported performance values are simulation predictions, not experimentally validated flight measurements.*
