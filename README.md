# Code for Survival of the Densest
Code to reproduce results presented in the work "Survival of the densest accounts for the expansion of mitochondrial mutations in ageing."
We provide source C code, that can be used to obtain all results presented in the paper. We also provide a Python Notebook of a minimal two-unit example.

C SOURCE CODE
Compile with (in gcc): 
gcc -g -Wall -o test source_code.c -lm

Requires math in GNU scientific library.
See comments before the start of the main programme for more details.


PYTHON NOTEBOOK
Requires NumPy and matplotlib (for plotting). 

Runninng time is heavily influenced by parameters like Nss, time of the simulation (T) and by the number of stochastic replicates of the evolution of the system (replicates). Running time for the parameters we use is ~ 3 minutes for 200 replicates on Google Colab.

# Simulated data
We also provide the simulated data for the plots in the paper (folder Simulated_data), both main text and SI appendix.
The data are organised by plot number and panel. Data from previously published experimental studies is not provided, see references in paper.
