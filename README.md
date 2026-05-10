# Design and Implementation of a Dual-Axis Solar Tracker

## Project Overview
[cite_start]This project addresses the efficiency gap in small-scale photovoltaic (PV) installations, where fixed mounts often capture only 60-70% of potential solar energy. [cite_start]I developed a low-cost, dual-axis tracking system designed to maintain a 5-15 W panel perpendicular to the sun's rays throughout the diurnal cycle[cite: 12, 25].

## Technical Design & Specifications
* [cite_start]**Mechanical Structure:** A rigid frame supporting orthogonal azimuth and elevation axes[cite: 27]. [cite_start]The frame was fabricated from wood to minimize mass and reduce actuator torque requirements[cite: 129, 256].
* [cite_start]**Control Architecture:** A hybrid approach combining LDR sensor feedback for real-time fine-tuning with sun-position logic for robustness during low-light conditions[cite: 13, 74].
* [cite_start]**Actuation:** Dual SG90 servo motors controlled via an Arduino Uno R3[cite: 130, 273].

## Engineering Selection Process
[cite_start]The final design (Design C) was selected through a weighted decision matrix evaluating energy gain, construction complexity, and maintenance requirements[cite: 175, 201].

| Criterion | Weight | Design A (Fixed) | Design B (Single-Axis) | Design C (Dual-Axis) |
| :--- | :--- | :--- | :--- | :--- |
| Energy Gain | 40% | 3/10 | 7/10 | 10/10 |
| Complexity | 15% | 10/10 | 7/10 | 5/10 |
| **Weighted Score** | **100%** | **6.35** | **7.20** | **7.55** |

## Key Outcomes
* [cite_start]**Performance:** Increased potential energy yield by 30-45% compared to static installations[cite: 37, 214].
* [cite_start]**Cost Efficiency:** Total system Bill of Materials (BOM) was optimized to approximately 3,270 KSh[cite: 273].
* [cite_start]**Accuracy:** Target tracking accuracy within $\pm 2-5^{\circ}$[cite: 119].
