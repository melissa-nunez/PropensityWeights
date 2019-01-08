# PropensityWeights
Study 58 was a randomized, community-based clinical trial that was designed to test for cognitive benefits from aerobic exercise. 
Of the individuals, some have neuroimaging (MRI and fMRI) data available while others do not. 

My goal was to explore the differences between individuals with and without neuroimgaing data, and use propensity scores to 
eliminate any possible, measured confounders. Using R statistical software, differences in baseline variables between individuals 
with and without neuroimgaing data available were calcualted. Using the significant variables, propensity scores were calculated. 
Ultimately, regression models were were created to test wether the propensity weights changed the associations between change in 
a neuroimaging variable and random treatment group.
