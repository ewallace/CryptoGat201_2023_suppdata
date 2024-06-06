# CryptoGat201_2023_suppdata

This repository is supplementary data accompanying the bioRxiv preprint:

> A trade-off between proliferation and defense in the fungal pathogen Cryptococcus at alkaline pH is controlled by the transcription factor GAT201.
> Elizabeth S. Hughes, Laura R. Tuck, Zhenzhen He, Elizabeth R. Ballou, Edward W.J. Wallace.
> bioRxiv preprint, 2024
> https://doi.org/10.1101/2023.06.14.543486

Data Analysis by Edward Wallace `Edward.Wallace@ed.ac.uk` and Liz Hughes `liz.hughes@ed.ac.uk`.

This repository holds most supplementary data and analysis for the paper:
 - budding index analysis
 - colony-forming unit assays
 - growth curve assays by plate reader
 - RT-qPCR

RNA-seq data analysis and homology analysis are in separate repositories:

- RNA-seq dataset 1 https://github.com/ewallace/CryptoWakeupRNASeq
- RNA-seq dataset 2 https://github.com/ewallace/CryptoGat201RNASeq
- Homology https://github.com/ewallace/Gat201homology_2022/


# Contents

Contents of the repository, listed by directory.

## Rmd

Data analysis scripts, in R markdown .Rmd format.
Also the .html format output.

- budding_index.Rmd - makes Figure 2B
- colony_forming_units_RPMI_RPMIserum.Rmd - makes Figure 2D
- growth_curves_GAT201_RPMI_YPD.Rmd - makes Figure 2C
- growth_curves_GAT201targets.Rmd - makes Figure 4E, Figure S10
- growth_curves_GAT204_LIV3.Rmd - makes  Figure S11
- growth_curves_GAT201_RPMIvCO2Indep.Rmd - makes Figure S12
- growth_curves_GAT201_RPMI_varyingNaHCO3.Rmd - makes Figure 5, Figure S13
- growth_curves_GAT201_RPMI_NaHCO3_vs_cAMP.Rmd - makes Figure S14
- RTqPCR_GAT201_complemented_strains.Rmd - makes Figure S6
- shared_functions_formatting.Rmd - shared packages, functions, and figure formatting that is called in all other data analysis scripts.

## data

Input data files in various tabular formats (.xlsx, .csv, .txt).

Contents here listed by the .Rmd analysis script that uses them.

### budding_index.Rmd

- 20220811_CryptoWakeup_Gat201_budding_quantification.xlsx

### colony_forming_units_RPMI_RPMIserum.Rmd

- 20221025_CFU60_RPMI_RPMIserum.csv

### growth_curves_GAT201_RPMI_YPD.Rmd

- 20200728_EH_PR2_RPMI_Setup.csv
- 20200728_EH_PR2_RPMI_WT_Gat201.xlsx
- 20200807_EH_PR4_YPD_Setup.csv
- 20200807_EH_PR4_YPD_WT_Gat201.xlsx


### growth_curves_GAT201targets.Rmd

- 20230308_RPMI_Gat201Targets_Plate1_setup.csv
- 20230308_RPMI_Gat201Targets_Plate1.xlsx
- 20230310_RPMI_Gat201Targets_Plate2_setup.csv
- 20230310_RPMI_Gat201Targets_Plate2.xlsx
- 20230321_RPMI_Gat201Targets_Plate3_setup.csv
- 20230321_RPMI_Gat201Targets_Plate3.xlsx


### growth_curves_GAT204_LIV3.Rmd

- 20240403_GAT204LIV3.xlsx
- 20240403_GAT204LIV3_Setup.csv


### growth_curves_GAT201_RPMIvCO2Indep.Rmd

- 20221216_PR27_RPMIvCO2Indep_Setup.csv
- 20221216_PR27_RPMIvCO2Indep.xlsx


### growth_curves_GAT201_RPMI_varyingNaHCO3.Rmd

- 20240112_SubGoal4_BR1_repeat.xlsx
- 20240112_SubGoal4_BR2_repeat.xlsx
- 20240112_SG4_BR3.xlsx
- 20240116_SG4_Plate-Setup.csv


### growth_curves_GAT201_RPMI_NaHCO3_vs_cAMP.Rmd

- 20240305_cAMP_Assay.xlsx
- 20240305_cAMP_Plate_Setup.csv


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


### growth_curves_GAT201targets.Rmd

- fig_growthcurves_Gat201Targets_RPMI_summary.png
- 20230308_RPMI_Gat201Targets_Plate1_splineplot.png
- 20230308_RPMI_Gat201Targets_Plate1_splineplot.svg

### growth_curves_GAT204_LIV3.Rmd

- fig_growthcurves_GAT204_LIV3.png


### growth_curves_GAT201_RPMIvCO2Indep.Rmd

- fig_growthcurves_RPMI_CO2independent.png


### growth_curves_GAT201_RPMI_varyingNaHCO3.Rmd

- fig_growthcurves_varyingNaHCO3_BioRep3.png
- fig_growthcurves_varyingNaHCO3_allreps.png


### growth_curves_GAT201_RPMI_NaHCO3_vs_cAMP.Rmd

- fig_growthcurves_NaHCO3_vs_cAMP.png


### RTqPCR_GAT201_complemented_strains.Rmd

- RTqPCR_GAT201_complemented_strains_deltadeltacq.png

