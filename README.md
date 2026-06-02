# 
Especificaciones:

Python 3.12.13

Pandas: 2.2.2

Matplotlib: 3.10.0

NumPy: 2.0.2

SciPy: 1.16.3

Instructions

For the notebook to work properly, all input files must be in .txt format and named using a sequential numbering system. The file range must be defined according to the total number of files available. For example, if your files are named name1.txt through name10.txt, the range should be defined as range(1,11). This is because Python includes the starting value but excludes the ending value, meaning that files 1 through 10 will be processed, while 11 will not be included.

Next, define the experimental parameters required for your analysis. In plot_lineal, these parameters are the same as those used in plot_modular, but they are defined directly without the self. prefix.

For plot_modular, the parameters are:

self.m: catalyst mass (g)
self.M: contaminant mass (g)
self.masa_molar_catalizador: catalyst molar mass (g/mol)
self.masa_molar_contaminante: contaminant molar mass (g/mol)
self.T: experimental temperature (K)

Afterward, define the UV–Vis plotting parameters, such as self.valores_primera = [] and self.valores_ultima = []. These variables determine the positions and values where the dashed reference lines will be displayed on the UV–Vis plot.

The variable self.lambda_objetivo defines the target wavelength that will be used for the photocatalytic calculations.

Finally, edit the arrows and their labels in the Graficar UVVis section (if using plot_modular) or in the Lineas y flechas section (if using plot_lineal). In these sections, the user manually specifies the degradation time and percentage values that will be displayed on the plots.

Once all these parameters have been configured, simply run all notebook cells to generate the plots and obtain the final results.




