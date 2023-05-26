# CryptoGat201_2023_suppdata

Supplementary data for forthcoming paper on Cryptococcus neoformans Gat201, May 2023.

Data Analysis by Edward Wallace `Edward.Wallace@ed.ac.uk` and Liz Hughes `liz.hughes@ed.ac.uk`.

This repository holds all supplementary data and analysis for the paper, except for RNA-seq.
RNA-seq data analysis is in separate repositories.

- [x] Budding index quantification of GAT201 mutants
- [x] Colony-Forming Units assay of GAT201 mutants 
- [x] Growth curves (plate reader) of GAT201 mutants
- [x] Growth curves (plate reader) in alternate buffered media
- [x] Growth curves (plate reader) of other mutants
- [x] RT-qPCR of GAT201 complemented strains


# Contents

## Rmd

Data analysis scripts, in R markdown format.

- budding_index.Rmd - Figure 2B
- colony_forming_units_RPMI_RPMIserum.Rmd - makes Figure 2D
- growth_curves_GAT201_RPMI_YPD.Rmd - makes Figure 2C
- growth_curves_GAT201_RPMIvCO2Indep.Rmd - makes Figure S5
- growth_curves_GAT201targets.Rmd - makes Figure 4E, Figure S11
- RTqPCR_GAT201_complemented_strains.Rmd - makes Figure S6
- shared_functions_formatting.Rmd - shared packages, functions, and figure formatting that is called in all other data analysis scripts.

## data

Input data files in various tabular formats (.xlsx, .csv, .txt).

Contents here listed by the .Rmd analysis script that uses them.

### budding_index.Rmd

- CryptoWakeup_Gat201_budding_quantification.xlsx

### colony_forming_units_RPMI_RPMIserum.Rmd

- 20221025_CFU60_RPMI_RPMIserum.csv

### growth_curves_GAT201_RPMI_YPD.Rmd

- 20200728_EH_PR2_RPMI_Setup.csv
- 20200728_EH_PR2_RPMI_WT_Gat201.xlsx
- 20200807_EH_PR4_YPD_Setup.csv
- 20200807_EH_PR4_YPD_WT_Gat201.xlsx

### growth_curves_GAT201_RPMIvCO2Indep.Rmd

- 20221216_PR27_RPMIvCO2Indep_Setup.csv
- 20221216_PR27_RPMIvCO2Indep.xlsx

### growth_curves_GAT201targets.Rmd

- 20230308_RPMI_Gat201Targets_Plate1_setup.csv
- 20230308_RPMI_Gat201Targets_Plate1.xlsx
- 20230310_RPMI_Gat201Targets_Plate2_setup.csv
- 20230310_RPMI_Gat201Targets_Plate2.xlsx
- 20230321_RPMI_Gat201Targets_Plate3_setup.csv
- 20230321_RPMI_Gat201Targets_Plate3.xlsx

### RTqPCR_GAT201_complemented_strains.Rmd

- 20221014_ComplementCheck_EH_Ct.txt


## results

Results files, mostly figures.

Contents here listed by the .Rmd analysis script that produces them.

### budding_index.Rmd

- budding_index_Time_Media_Temp.png
- budding_index_Time_Media_Temp.svg

### colony_forming_units_RPMI_RPMIserum.Rmd

- cfu_mean_plot_all_RRS.png
- cfu_mean_plot_all_RRS.svg

### growth_curves_GAT201_RPMI_YPD.Rmd

- 20200728_EH_PR2_RPMI_WT_Gat201_summaryplot.png
- 20200807_EH_PR4_YPD_WT_Gat201_summaryplot.png
- fig_growthcurves_GAT201_RPMI_YPD.svg
- fig_growthcurves_GAT201_RPMI_YPD.png

### growth_curves_GAT201_RPMIvCO2Indep.Rmd

- fig_growthcurves_RPMI_CO2independent.png

### growth_curves_GAT201targets.Rmd

- fig_growthcurves_Gat201Targets_RPMI_summary.png
- 20230308_RPMI_Gat201Targets_Plate1_splineplot.png
- 20230308_RPMI_Gat201Targets_Plate1_splineplot.svg

### RTqPCR_GAT201_complemented_strains.Rmd

- RTqPCR_GAT201_complemented_strains_deltadeltacq.png

