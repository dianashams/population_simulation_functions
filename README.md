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

**The primary goal of these functions is to provide an easy way to create simulated datasets for testing 
various classification and survival analysis prediction models.**

Please note that all numbers and names are fictional and do not represent observed health dependencies. 

All questions please send to diana.shamsutdinova@kcl.ac.uk
