# Modified DICE 2023 Model with Carbon Budget Constraint

This repository contains a modified version of the **DICE 2023** integrated assessment model, originally developed by William Nordhaus. The original model can be accessed at [williamnordhaus.com/dicerice-models](https://williamnordhaus.com/dicerice-models).

## Key Modifications

- **Carbon Budget Constraint**: A new constraint has been introduced to limit the cumulative carbon emissions between **2020 and 2100** to **1000 GtCO₂**.
- **Reduced Time Horizon**: The number of time periods in the model has been shortened to ensure compatibility with the **free version of GAMS**, which imposes size limits on model runs.

## Purpose

These modifications allow users to:
- Analyze the implications of a strict global carbon budget.
- Run the model on the free version of GAMS without requiring a full license.

## Files and Descriptions

### 📄 Model Files

- `DICE2023-b-4-3-10.gms`:  
  Main GAMS model file used to run the modified DICE 2023 model.

- `Include/`:  
  Folder containing supporting GAMS modules, which are called from within the main model file.

### 📊 Output Data Files

- `DICE2023-b-4-3-10_NOBC.csv`:  
  Full model output without any carbon budget constraint applied.

- `DICE2023-b-4-3-10_BC.csv`:  
  Full model output **with** the carbon budget constraint (1000 GtCO₂ from 2020–2100).

### 📈 Comparison Excel Files

- `TOT_Carbon_Emission_GTCO2_PY.xlsx`:  
  Contains comparison graphs (NOBC vs BC) for **Total Carbon Emissions (GtCO₂/year)** across selected scenarios.

- `CO2_Concentration_PPM.xlsx`:  
  Contains comparison graphs (NOBC vs BC) for **Atmospheric CO₂ Concentration (PPM)**.

- `ATM_TEMP.xlsx`:  
  Contains comparison graphs (NOBC vs BC) for **Atmospheric Temperature (°C above preindustrial levels)**.

---

## License & Attribution

The base model is developed and maintained by William Nordhaus and collaborators. Please cite appropriately if you use or modify this version in your work.

---

Feel free to open issues or contribute improvements.
