# PropensityWeights
Study 58 was a randomized, community-based clinical trial that was designed to test for cognitive benefits from aerobic exercise. 
Of the individuals, some have neuroimaging (MRI and fMRI) data available while others do not. 

My goal was to explore the differences between individuals with and without neuroimgaing data, and use propensity scores to 
eliminate any possible, measured confounders. Using R statistical software, differences in baseline variables between individuals 
with and without neuroimgaing data available were calculated. Using the significant variables, propensity scores were calculated. 
Ultimately, regression models were were created to test whether the propensity weights changed the associations between change in 
a neuroimaging variable and random treatment group.

In the "Study58_SubCorVol_IPTW.Rmd" file, a series of subcortival volumes were used as the outcome of linear regression models to asses whether they differe between random groups, accounting for other variables. The models with and without propensity weights were compared.
