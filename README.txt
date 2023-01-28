S4 Supplemental Section to the manuscript "E-DES-PROT: A novel computational model to describe the effects of amino acids and protein on postprandial glucose and insulin dynamics in humans".
E-DES-PROT model MATLAB implementation
Matlab version: R2018b

CONTENTS:
run_model.m 		- script to run model.

diffeq_diabetes.m 	- model equations
errorFunction.m 	- error function for optimization
integratorfunG.m 	- integrator function for integral part of PID insulin model
load_pHealthy_c.m 	- parameters and constants
load_x0_input.m		- initialize inputs
example_data.csv 	- example data set from literature containing leucine, glucose, and insulin concentrations following leucine ingestion. 

example_figure.png 	- running the run_model.m file should produce this plot. Note that slight differences due to default settings of the optimizer in different MATLAB versions might occur.

USE:
Open and execute the run_model.m file in Matlab.

For reproducibility, running run_model.m without changes should result in the figure example.png.