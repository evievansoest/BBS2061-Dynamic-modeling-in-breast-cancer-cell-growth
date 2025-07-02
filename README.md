# BBS2061-Dynamic-modeling-in-breast-cancer-cell-growth

This repository contains a MATLAB script to simulate tumor growth dynamics affected by chemotherapy and anti-VEGF drugs.

## Features

- Models cancer, endothelial cells, VEGF, chemotherapy, and anti-VEGF drugs.
- Includes drug dosing with capped maximum concentrations.
- Generates plots of tumor volume, VEGF levels, endothelial cells, and drug concentrations.
- Saves plots as PNG images to the `results/` folder.

## How to run

1. Open MATLAB.
2. Run the script `TumorGrowthModel.m`.
3. Plots will display and be saved automatically to the `results/` folder.

## Parameters

All model parameters and dosing schedules can be edited inside the script under the `params` struct.

Happy modeling!
