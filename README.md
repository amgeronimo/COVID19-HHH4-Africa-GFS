# Tracking and predicting the African COVID-19 pandemic

### This code is a modification of the model and visualization found in "Pan-African evolution of within- and between-country COVID-19", *Proceedings of the National Academy of Sciences* (PNAS), July 13, 2021 118 (28) e2026664118, https://www.pnas.org/content/118/28/e2026664118. with GitHub code [here](https://github.com/Schiff-Lab/COVID19-HHH4-Africa/). 

A visualization of the model inputs and published results can be found at our [R-shiny server](https://www.schiff-lab-webapps.esm.psu.edu/COVID19-HHH4-Africa-GFS/)

Set the working directory to the one with these source files, and run these files:

- `01_data-processing-model.R`: cleans and processes the input data in `data/original` and gets it ready for modelling. The output of this script goes into the `data/processed` folder.

- `01_data-processing-plot.R`: cleans and processes the input data in `data/original` and gets it ready for plotting. The output of this script goes into the `data/processed` folder.

- `02_modelfitting.R`: uses the processed data to fit the models and saves them in `output/models/`. Summary tables are also produced and saved in `output/tables`.

- `03_figures-model.R`: uses fitted model to create figures in the `figs` folder.

- `03_figures_aux.R`: use processed data and fitted model to create other figures in the `figs` folder.

The `R` folder contains the `functions.R` file that has a set of costum functions needed to run the code. 


