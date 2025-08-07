# Modified DICE 2023 Model with Carbon Budget Constraint

This repository contains a modified version of the **DICE 2023** integrated assessment model, originally developed by William Nordhaus. The original model can be accessed at [williamnordhaus.com/dicerice-models](https://williamnordhaus.com/dicerice-models).

## Key Modifications

- **Carbon Budget Constraint**: A new constraint has been introduced to limit the cumulative carbon emissions between **2020 and 2100** to **1000 GtCO₂**.
- **Reduced Time Horizon**: The number of time periods in the model has been shortened to ensure compatibility with the **free version of GAMS**, which imposes size limits on model runs.

## Purpose

These modifications allow users to:
- Analyze the implications of a strict global carbon budget.
- Run the model on the free version of GAMS without requiring a full license.

## License & Attribution

The base model is developed and maintained by William Nordhaus and collaborators. Please cite appropriately if you use or modify this version in your work.

---

Feel free to open issues or contribute improvements.
