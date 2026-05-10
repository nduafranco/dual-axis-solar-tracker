# Design and Implementation of a Dual-Axis Solar Tracker

## Project Overview
This project addresses the efficiency gap in small-scale photovoltaic (PV) installations, where fixed mounts often capture only 60-70% of potential solar energy. I developed this low-cost, dual-axis tracking system designed to maintain a 5-15 W panel perpendicular to the sun's rays throughout the diurnal cycle.

## Technical Design & Specifications
**Mechanical Structure:** A rigid frame supporting orthogonal azimuth and elevation axes. The frame was fabricated from wood to minimize mass and reduce actuator torque requirements.

**Control Architecture:** A hybrid approach combining LDR sensor feedback for real-time fine-tuning with sun-position logic for robustness during low-light conditions.

**Actuation:** Dual SG90 servo motors controlled via an Arduino Uno R3.

## Engineering Selection Process
The final design (Design C) was selected through a weighted decision matrix evaluating energy gain, construction complexity and maintenance requirements.

| Criterion | Weight | Design A (Fixed) | Design B (Single-Axis) | Design C (Dual-Axis) |
| :--- | :--- | :--- | :--- | :--- |
| Energy Gain | 40% | 3/10 | 7/10 | 10/10 |
| Complexity | 15% | 10/10 | 7/10 | 5/10 |
| **Weighted Score** | **100%** | **6.35** | **7.20** | **7.55** |

## Key Outcomes
**Performance:** Increased potential energy yield by 30-45% compared to static installations.
**Cost Efficiency:** Total system Bill of Materials (BOM) was optimized to approximately 3,270 KSh.
**Accuracy:** Target tracking accuracy within $\pm 2-5^{\circ}$.
