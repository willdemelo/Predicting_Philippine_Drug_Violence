# Predicting Drug-Related Executions during the Philippine Drug War
This project reproduces a negative binomial model from Religious Protection from Populist Violence: The Catholic Church and the Philippine Drug War (Brooke et al., 2023). Specifically, it replicates the fourth and most complex model from Table 1 (p. 213) of the original study.

## Objective
The study examines the influence of Roman Catholic parishes on the number of drug-related killings in barangays (smallest administrative units) within the National Capital Region of the Philippines during Rodrigo Duterte’s administration. The model assesses whether the presence of a parish correlates with a reduction in extrajudicial killings.

## Methodology
Dataset: The analysis is based on publicly available data on drug-related executions and religious institutions.
Modeling Approach: A negative binomial regression is used to account for overdispersion in the count data.
Reproduction Effort: This project follows the methodology outlined in Brooke et al. (2023) to validate the robustness of their findings.
## Repository Contents
data/: Contains the dataset used for modeling.
notebooks/: Includes scripts for data preprocessing and statistical analysis.
results/: Stores output tables and visualizations.
## Citation
If using this work, please cite the original article: Brooke, et al. (2023). Religious Protection from Populist Violence: The Catholic Church and the Philippine Drug War. American Journal of Political Science.
