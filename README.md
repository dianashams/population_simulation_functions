# population_simulation_functions
The two files contain functions that simulate artificial samples with 
- 1 binary output (1/0) or 
- 2 longitudinal output (binary output + observation time during which this output was observed)
There three functions to generate a sample with linear, non-linear or cross-term dependencies between the predictors 
("age", "bmi", "gender", "hyp" for hypertention) and the outcome ("heart failure"). 

The primary goal was to create simulated datasets to test and coompare 
performance of various classification and survival analysis models. 
