# BatteryEQOptimizer

**BatteryEQOptimizer** is a Python tool for optimizing the health and performance of lead-acid battery banks. It helps monitor battery cell differences, applies temperature corrections to specific gravity (SG) readings, identifies cells needing equalization, and provides visual tracking of SG differences to ensure balanced performance. A video on the tool can be found at: https://youtu.be/iZQzWT-ukwU?si=3TYrTyvEihXNOCkS.

## Features
- **Temperature Correction**: Automatically adjusts SG readings based on electrolyte temperature.
- **Equalization Detection**: Calculates SG differences between cells to identify batteries that may require equalization treatments.
- **Color-Coded Visualization**:
  - **Green**: SG difference < 0.01
  - **Yellow**: 0.01 ≤ SG difference < 0.02
  - **Red**: SG difference ≥ 0.02
- **Summary Statistics**: Calculates bank-level statistics including average SG and maximum difference between cells.
- **Equalization Tracking**: Records total equalization time and number of treatments for each battery.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nativesci/BatteryEQOptimizer.git
