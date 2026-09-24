# BAMS MLD analysis 

#### This repository contains all necessary code for producing the final Mixed Layer Depth figures in the Southern Ocean section of the 2025 Bulletin of American Meteorological Society State of the Climate Report.

#### Complete Report: Blunden, J. and J. Reagan, Eds., 2026: “State of the Climate in 2025”. Bull. Amer. Meteor. Soc., 107 (8), Si–S512, https://doi.org/10.1175/2026BAMSStateoftheClimate.1.

#### Chapter, Antarctica and the Southern Ocean: Raphael, M. N. and K. R. Clem, 2026: Antarctica and the Southern Ocean [in “State of the Climate in 2025“]. Bull. Amer. Meteor. Soc., 107 (8), S352–S396, https://doi.org/10.1175/BAMS-D-26-0127.1.

#### Updated raw Argo / Roemmich and Gilson data compiled and preprocessed for MLD analysis in `ML_RG_Argo_Preprocessing_BAMS2025.ipynb`.

#### MLD is computed as the maximum depth where surface-referenced potential density no longer exceeds 0.03 kg/m3 more than potential density at 10 m depth, following de Boyer Montegut et al (2004). MLD fields and calculated and saved out in `MixedLayer_RG_Calculation_CreateFiles_BAMS2025.ipynb`.

#### Final figures as they appear in the 2025 report are produced in `Final_Figures2025.ipynb`. Anomalies are reported relative to 2004->2020 time mean.