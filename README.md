# tecator

All details about the exercise and data can be found here: https://www.openml.org/search?type=data&sort=runs&id=505&status=active

Here, the goal is to analyze the dataset and predict the variable “fat” using machine learning methodologies.

Main script: Tecator - ARazetti 4 Usense.ipynb

Results and methodology are summarized here: https://docs.google.com/presentation/d/1vji543cdNZ1sYop-2QJWnrvxKXrRKqssRsSyIu1ChqY/edit#slide=id.p

## Data summary

For each meat sample the data consists of a 100 channel spectrum of absorbances and the contents of moisture (water), fat and protein. The absorbance is -log10 of the transmittance measured by the spectrometer. The three contents, measured in percent, 
are determined by analytic chemistry.

There are 240 samples which are divided into 5 data sets for the purpose 
of model validation and extrapolation studies. 

The data for all 240 samples appear at the end of this file - 25 lines per sample. 

The spectra are preprocessed using a principal component analysis, and the first 22 principal components (scaled to unit variance) are included for each sample.
