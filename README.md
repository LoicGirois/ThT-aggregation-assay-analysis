# ThT-aggregation-assay-analysis
A jupyter notebook allowing to determine curve parameters by fitting using logistic curve as a model.

Short description:
Aggregation experiments can be performed using Thioflavin T as a probe to follow in real time the aggregation. In order to analyse the data from different conditions in a fast and reproducible manner a program was written. By fitting the curves to the logistic function, it is possible to extract kinetic parameters from the curves to facilitate comparisons. 

Data loading:
The program is loading the data from a spreadheets where the raw data is stored as columns in either excel or csv format. See example excel file in the folder.

Outputs:
all graphics produced can be saved using right clic, three csv files will be produced in the same folder as the datafile: one containing the logistic fitting parameters and their respective errors (fitting), one with the fluorescence, timestones and information on potential problems encountered (analysis) and a last file containing the modified curves generated during the analysis (curves).
