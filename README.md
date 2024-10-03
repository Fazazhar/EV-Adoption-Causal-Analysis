# Evaluating the Relationship of EV Charging Station on the Uptake of Electric Vehicles

## Paper Overview

This repository highlights the research paper titled **"Evaluating the Relationship of EV Charging Station on the Uptake of Electric Vehicles — Implication of the NEVI Formula Program."** The study examines the impact of electric vehicle (EV) charging infrastructure on the adoption rates of electric vehicles, with a particular focus on the implications of the NEVI Formula Program.

## Abstract

To achieve the federal goal to make half of all new vehicles sold in the U.S. in 2030 zero-emissions vehicles, the U.S. Department of Transportation’s (DOT) Federal Highway Administration (FHWA) has employed the National Electric Vehicle Infrastructure (NEVI) Formula Program, which aims to promote the interconnected network of publicly accessible electric vehicle (EV) charging stations. By analyzing panel data on a subset of U.S. counties, this paper examines the relationship between different classes of EV charging stations towards plug-in hybrid electric vehicles (PHEVs) and battery electric vehicles (BEVs). Though an instrumental approach in identifying potential endogeneity, this study suggests that public charging stations and the implication of the NEVI formula program might not pose the optimistic benefit in achieving the federal goal. This finding indicates the need to reevaluate current strategies and explore additional incentives to enhance the adoption of EVs and the effectiveness of public charging infrastructure.


## Full Paper

The full text of the paper can be found in the following file:

[EV Adoption Memo.pdf](analysis/EV_adoption_memo.pdf)

### Supplementary Materials

1. **Data Wrangling and Feature Engineering**
   - The detailed processes of data wrangling and feature engineering can be found in the following QMD file:
   - [Data Wrangling and Feature Engineering.qmd](analysis/part1_wrangling.qmd)

2. **Data Estimation and Causal Analysis**
   - The methodology and results for data estimation and causal analysis are outlined in the following QMD file:
   - [Data Estimation and Causal Analysis.qmd](analysis/part2_estimation.qmd)

## Key Findings

1. **Limited Impact of Public Charging Stations**: The analysis revealed that an increase in public charging infrastructure positively influences the adoption of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs), with average increases of approximately 0.74 and 0.132 units, respectively. However, the overall significance of this relationship was minimal, suggesting that simply expanding public charging stations may not substantially drive EV adoption.

2. **Counterintuitive Effects of NEVI Funding**: When employing NEVI funding as an instrumental variable, the study observed a surprising inverse relationship, indicating that an increase in public charging stations, funded by NEVI, resulted in a decrease of approximately 1.48 BEVs and 0.36 PHEVs per unit of charging station. This finding challenges the initial hypothesis and raises concerns about the efficacy of the NEVI program in promoting EV adoption.

3. **Variability Among Vehicle Types**: The study found that the impact of public charging stations differed across vehicle types. Notably, trucks and larger vehicles demonstrated a more pronounced increase in adoption with the addition of charging infrastructure, especially for BEVs. This suggests that certain vehicle categories may benefit more significantly from enhanced charging access.

4. **Need for Alternative Instrumental Variables**: The analysis highlighted potential limitations of using NEVI funding as an instrumental variable due to its early-stage implementation and associated uncertainties. Future research may benefit from exploring alternative instruments, such as GIS-based metrics of highway access, which could provide a more robust causal inference regarding the relationship between charging infrastructure and EV adoption.

## Acknowledgments

I would like to express my sincere gratitude to my advisor, **Prof. Craig McIntosh**, and **Prof. Jen Burney**, for their invaluable guidance and support throughout the course of this research. Their insights and encouragement were instrumental in shaping this study.


## Contact

For further inquiries or discussions regarding this paper, please contact me at through [LinkedIn](https://www.linkedin.com/in/farrel-azhar-6b8179236/)
