# BBS2061-Dynamic-modeling-in-breast-cancer-cell-growth

This repository contains MATLAB scripts to simulate tumor growth dynamics influenced by chemotherapy and anti-VEGF drugs.

## Features

### Dynamic_model_breastcancer
- Models cancer cells, endothelial cells, VEGF, chemotherapy, and anti-VEGF drugs.  
- Includes drug dosing with capped maximum concentrations.  
- Generates plots of tumor volume, VEGF levels, endothelial cells, and drug concentrations.  

### Chemo_antiVEGF_sim
- Models combined drug efficacy when chemotherapy and anti-VEGF drugs are administered together.  
- Includes multiple dosing schedules for both anti-VEGF and chemotherapy drugs.

### Tumor_model_sensitivityanalysis
- Generates bar plots to analyze parameter sensitivity.  
- Provides tables summarizing sensitivity results.

## How to run

1. Open MATLAB.  
2. Run any of the scripts, for example `Dynamic_model_breastcancer`.  
3. Plots will display and be saved automatically to the `results/` folder.

## Parameters

All model parameters and dosing schedules can be edited inside each script under the `params` struct.

Happy modeling!

