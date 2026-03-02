# GreyBox-model-heatloss-PTES

This notebook implements **Grey Box models** for predicting heat loss for a pit thermal energy storage (PTES) system. 
The models combines a resistance–capacitance (RC) thermal model with differential evolution (DE) to identify thermal properties directly from monitoring data. 

## Overview
- **Inputs**: water temperatures, air temperature, the geometry of the pit.
- **Output**: Predicted heat loss.
- **Use case**: Fit a given model structure to your data, then use it for analysis or control.


## Models
   - **5R2C**: 5 resistances, 2 capacitances
   - **6R2C**: 6 resistances, 2 capacitances
   - **7R3C**: 7 resistances, 3 capacitances 
   - **10R4C**: 10 resistances, 4 capacitances (e.g. two side layers: `waterside1`, `waterside2`).
   - **10R5C**: 10 resistances, 5 capacitances (2nd order)

## File
- **Greybox_heatloss_GitHub.ipynb**: Single notebook containing data loading, geometry, all model variants (5R2C–10R5C), and evaluation/plotting.
