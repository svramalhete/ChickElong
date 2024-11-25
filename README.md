# A Morphometric Characterization of Early Chick Embryo Elongation
This R project contains the data collected from an experimental study to characterize the ckick elongation in early stages. The dataset as well as R notebook is available here.

These data were provided by Prof. Raquel P. Andrade (rgandrade@ualg.pt), and Ana Cristina Maia-Fernandes (ac.maia.fernandes@gmail.com), from Universidade do Algarve, Faro, Portugal.

## Citation
Maia-Fernandes, A.C., Pais de Azevedo, T., Ramalhete, S.V., Martins, G., Palmeirim, I., Duarte, I., Martel, P., Marreiros, A., Andrade, R.P., “A Morphometric Characterization of Early Chick Embryo Elongation”, Development Biology (2024) (Submitted)

## Usage
This R project was built to ChickElongQuant_input.csv dataset (available in the main folder).

## Project Structure
- |-- README.md                      # Project documentation
- |-- ChickElong_Measurements.Rmd    # Notebook to the data analysis
- |-- ChickElongQuant_input.csv      # Input file
- |-- Optimal Binning.sav            # SPSS Script for Optimal Binning
- |-- output/                        # Directory for output files
- |   |-- correlation.svg            # Output file
- |   |-- Crecimento_Norm.svg        # Output file
- |   |-- Crescimento.svg            # Output file
- |   |-- Elongation_rate.svg        # Output file
- |   |-- HHvsLen.svg                # Output file
- |   |-- ridgeplot_overlap1.pdf     # Output file
- |   |-- ridgeplot_overlap2.pdf     # Output file
- |   |-- ridgeplot_overlap3.pdf     # Output file
- |   |-- ridgeplot_overlap4.pdf     # Output file
- |   |-- ridgeplot_overlap5.pdf     # Output file
- |   |-- ridgeplot_overlap6.pdf     # Output file
- |   |-- ridgeplot_overlap7.pdf     # Output file
- |   |-- ridgeplot_overlap8.pdf     # Output file
- |   |-- ridgeplot_overlap9.pdf     # Output file
- |   |-- ridgeplot_time9.pdf        # Output file
- |   |-- Output_SPSS.pdf            # Output file

## Dependencies
R packages required to run the project:
- dplyr, tidyverse, and magrittr - needed to manipulate data;
- ggplot2, ggthemes, GGally, viridis, and ggridges - needed to visualize data;
- FactoMineR and factoextra - needed to perform the PCA analysis and visualization.

## Contact
Sara V. Ramalhete (saravramalhete@gmail.com)
