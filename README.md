# Predicting Drug-Related Executions during the Philippine Drug War
This project reproduces and modifies a negative binomial model from Religious Protection from Populist Violence: The Catholic Church and the Philippine Drug War (Brooke et al., 2023). Specifically, I replicate the fourth and most complex model from Table 1 (p. 213) of the original study.

## Project Overview
The original study examined the influence of Roman Catholic parishes on the number of drug-related killings in barangays (the smallest administrative units) within the National Capital Region of the Philippines during Rodrigo Duterte’s administration. The model assesses whether the presence of a parish correlates with a reduction in extrajudicial killings. I make some additions to the original model which significantly improve its fit and ability to predict, and re-evaluate the authors' original claim that having a Catholic parish reduces the expected number of drug-related killings in a given barangay.

## Resources
 - Editor Used: RStudio
 - R Version: R 4.4.2 

### knitr
This writeup was produced as a Quarto Markdown (.qmd) file, which allows for greater ease of rendering and publishing documents produced in RStudio. The knitr package helped me render the writeup in a neat, concise format as a .pdf file.

### ggplot2
For the visualizations I produced in this project, I used ggplot2 - namely to track the distribution of drug-related killings across the NCR, and to assess the significance of the relationship between Catholic parish presence and drug-related killings across NCR provinces.

### stargazer
The stargazer package lets me assemble all of my regression outputs in a concise, tabular format, allowing for ease of interpretation.

## Bibliography
If using this work, please cite the original article:
Brooke, Steven, David Buckley, Clarissa David, and Ronald Mendoza. 2023. "Religious Protection from Populist Violence: The Catholic Church and the Philippine Drug War. American Journal of Political Science 67 (1): 205-220. [https://doi.org/10.1111/ajps.12669](https://doi.org/10.1111/ajps.12669)

