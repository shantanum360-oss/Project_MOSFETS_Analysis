# Temperature-Dependent Analysis of Cascode MOSFET Amplifiers

A simulation-based study investigating the influence of temperature variations on the performance of cascode MOSFET amplifiers. This project combines LTSpice simulations with Python-based analysis to evaluate the behavior of analog amplifier circuits under varying operating conditions.

## Overview

This project was carried out under the Materials Society, IIT Kanpur, with the objective of understanding how temperature affects the electrical characteristics and overall performance of cascode MOSFET amplifiers.

The study focuses on analyzing key analog performance metrics across different temperatures, semiconductor materials, and bias conditions to derive design insights for robust analog circuit design.

## Objectives

* Develop a simulation framework to analyze temperature effects on cascode MOSFET amplifiers.
* Evaluate amplifier performance under varying temperatures and operating conditions.
* Compare material-dependent behavior and quantify performance degradation mechanisms.
* Derive design recommendations for temperature-resilient analog circuits.

## Methodology

### LTSpice Simulations

* Simulated cascode MOSFET amplifier circuits using LTSpice.
* Performed simulations across a wide range of temperatures.
* Investigated the impact of different semiconductor materials and bias conditions.

### Small-Signal Analysis

Analyzed key amplifier parameters including:

* Voltage Gain
* Bandwidth
* Transconductance (gm)
* Output Resistance (ro)

### Python-Based Analysis

Used Python for:

* Data processing and analysis
* Material comparison studies
* Noise modeling
* Visualization and plotting of simulation results

## Technologies Used

* LTSpice
* Python
* NumPy
* Pandas
* Matplotlib

## Repository Structure

```text
Temperature-Dependent-MOSFET-Analysis/
│
├── README.md
├── LTSpice_Simulations/
│   ├── Cascode_Amplifier.asc
│   ├── Simulation_Results/
│   └── Netlists/
│
├── Python_Analysis/
│   ├── data_processing.py
│   ├── visualization.py
│   └── noise_analysis.py
│
├── Data/
│   ├── simulation_outputs.csv
│   └── processed_data.csv
│
├── Figures/
│   ├── gain_vs_temperature.png
│   ├── bandwidth_vs_temperature.png
│   └── material_comparison.png
│
├── Reports/
│   └── project_report.pdf
│
└── future_work.md
```

## Key Analysis

### Temperature Sweep Analysis

* Investigated amplifier characteristics across varying temperatures.
* Studied the degradation of device performance with increasing temperature.

### Material Comparison

Compared the performance of different semiconductor materials based on:

* Gain
* Bandwidth
* Carrier mobility
* Noise characteristics

### Noise Modeling

* Evaluated the effect of temperature on amplifier noise.
* Analyzed noise trends for different material systems.

