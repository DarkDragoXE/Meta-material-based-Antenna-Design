# Metamaterial-Inspired Antenna Design

This repository documents the design, simulation, and analysis of a metamaterial-inspired microstrip antenna with emphasis on compactness, dual/multi-band operation, and adaptability for sub-6 GHz communications (e.g., ~2 GHz and ~4.5–5 GHz), Wi-Fi, radar, and IoT applications.

---

## Objectives
- Develop a compact microstrip antenna using metamaterial concepts (e.g., CRLH transmission lines, ZOR).
- Target multi-band operation suitable for modern wireless standards.
- Explore beam behavior and polarization strategies for robust links.
- Optimize S-parameters, VSWR, radiation pattern, and gain.

---

## Methods and Tools
- **Ansys HFSS**: Full-wave 3D EM simulation (geometry, S11/VSWR, radiation patterns).
- **Keysight ADS**: Circuit co-simulation and impedance matching.
- Optional: MATLAB/Python for post-processing plots and data checks.

**Design workflow**
1. Establish baseline microstrip geometry and run parametric sweeps (substrate, patch, slots).
2. Introduce metamaterial loading (CRLH-inspired features) for miniaturization and bandwidth shaping.
3. Iterate feed and matching networks; validate S11, axial ratio, and gain.
4. Compare single- vs multi-band intents; finalize layout.

---

## Results (Summary)
- Dual-/multi-band response observed in the sub-6 GHz range (e.g., near ~2 GHz and ~4.5–5 GHz).
- Strong return-loss performance in the higher band; acceptable match in the lower band after metamaterial loading.
- Radiation patterns consistent with a compact planar form factor; directivity suitable for wireless links.
- Fabrication-friendly planar structure with reduced footprint compared to conventional patches.
