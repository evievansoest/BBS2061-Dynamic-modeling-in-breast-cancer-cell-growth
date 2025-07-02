# BBS2061-Dynamic-modeling-in-breast-cancer-cell-growth

This repository contains a MATLAB script to simulate tumor growth dynamics affected by chemotherapy and anti-VEGF drugs.

## Features

**Dynamic_model_breastcancer**

- Models cancer, endothelial cells, VEGF, chemotherapy, and anti-VEGF drugs.  
- Includes drug dosing with capped maximum concentrations.  
- Generates plots of tumor volume, VEGF levels, endothelial cells, and drug concentrations.  
- Saves plots as PNG images to the `results/` folder.  

**Chemo_antiVEGF_sim**

- Models total drug efficacy upon adding drugs.  
- Includes several dosages of anti-VEGF and chemotherapy.  

**Tumor_model_sensitivityanalysis**

- Models bar plot with parameters for sensitivity.  
- Table with them.  

## How to run

1. Open MATLAB.  
2. Run the script `TumorGrowthModel.m` ... or another relevant script.  
3. Plots will display and be saved automatically to the `results/` folder.  

## Parameters

All model parameters and dosing schedules can be edited inside the script under the `params` struct.

Happy modeling!

---

*This project was developed as part of the BBS2061 course at Maastricht University.*
