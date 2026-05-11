Massive MIMO assignment including Colab simulation code and optimized output results
# Topic 5: Massive MIMO Antenna Panel Deactivation

## Project Description
This project evaluates traffic-aware antenna panel deactivation for an energy-efficient Massive MIMO base station. It compares an always-on baseline with balanced and aggressive adaptive strategies under low, medium, and peak traffic conditions.

## Assignment Alignment
The simulation includes:
- Component-based base station power model
- Massive MIMO antenna panel deactivation
- MRT beamforming
- Spatial user distribution with angular spread
- SINR, throughput, and coverage probability evaluation
- Synthetic diurnal traffic input
- Baseline versus proposed strategies across three traffic load scenarios
- Sensitivity testing of coverage probability versus SINR threshold

## Simulation Tool
Google Colab with Python.

## Required Libraries
- numpy
- pandas
- matplotlib

## How to Run
1. Open `Topic5_Massive_MIMO_Panel_Deactivation.ipynb` in Google Colab.
2. Run all cells from top to bottom.
3. The notebook will generate numerical outputs, figures, parameter files, and a ZIP archive automatically.
4. Download the generated files after execution.

## Main Parameters
- Massive MIMO array: 64T64R
- Number of panels: 8
- Antennas per panel: 8
- Cell radius: 500 m
- Bandwidth: 20 MHz
- Transmit power: 43 dBm
- Noise power: -94 dBm
- Main SINR threshold: 2.4 dB
- Monte Carlo trials: 300

## Traffic Scenarios
- Low Load: 5 users
- Medium Load: 15 users
- Peak Load: 30 users

## Strategies
1. Baseline Always-On: 8 panels for all loads
2. Balanced Adaptive: 4 panels for low load, 6 panels for medium load, 8 panels for peak load
3. Aggressive Adaptive: 2 panels for low load, 4 panels for medium load, 8 panels for peak load

## Output Files
- `simulation_results_final.csv`
- `sensitivity_results_coverage_vs_sinr_threshold.csv`
- `simulation_parameters_final.txt`
- `Figure_0_Synthetic_Diurnal_Traffic_Profile.png`
- `Figure_1_Power_Consumption.png`
- `Figure_2_Energy_Saving.png`
- `Figure_3_Average_SINR.png`
- `Figure_4_Average_Throughput.png`
- `Figure_5_Coverage_Probability.png`
- `Figure_6_Energy_Saving_vs_Coverage.png`
- `Figure_7_Sensitivity_Coverage_vs_SINR_Threshold.png`
