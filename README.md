# population_simulation_functions
The two files contain functions that simulate artificial samples with 
- 1 binary output (1/0) or 
- 2 longitudinal output (binary output + observation time during which this output was observed)

Each file contains three functions that generate samples with 
* linear, 
* non-linear or 
* cross-term 

dependencies between the predictors and the outcome. 

Predictors are "age", "bmi", "gender", "hyp" for hypertention, the outcome is ("heart failure"). 
All numbers and names are fictional and do not represent observed health dependencies. 

The primary goal of these functions are to provide an easy way to create simulated datasets for testing 
various classification and survival analysis prediction models. 
