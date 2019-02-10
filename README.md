# Glynis Daniels
# The US Opioid Epidemic: 
# Predicting Mortality From Community Characteristics
# January 2019

1. [Project Final Report](./US_Opioid_Epidemic_Glynis_Daniels_2019.pdf)
2. Python Notebooks
	1. [Introduction: The US Opioid Epidemic](./1%20Introduction%20-%20US%20Opioid%20Epidemic.ipynb)
	2. [Census Data Processing](./2%20Census%20Data%20Processing.ipynb)
	3. [Merge and Clean Data](./3%20Merge%20and%20Clean%20Data.ipynb)
	4. [Exploratory Analysis](./4%20Exploratory%20Analysis.ipynb)
	5. [Data Modeling](./5%20Data%20Modeling.ipynb)
3. [Data Files](./Data)


## Executive Summary

The United States is currently in the midst of an opioid crisis that is causing record numbers of overdose deaths. This epidemic is not equally felt in all areas of the country, however. In fact the distribution of overdose deaths is highly skewed, with some places experiencing exponential increases and others barely impacted. Efforts to address the problem could be made more effective by predicting which regions of the country will be most impacted and by understanding what socioeconomic characteristics are associated with high rates of addiction. This project utilizes data on drug overdose mortality from NCHS combined with socioeconomic data from the US Census to build a predictive model. Several modeling techniques are tested using cross-validation. After hyperparameter tuning, the best observed model is a nonlinear support vector regression machine. This model achieves an R-square of 0.60. 

The nonlinear support vector machine model operates as a ‘black box’, and cannot assess relative feature importance. But descriptive information from predicted mortality rates appears to be generally consistent with bivariate analysis. Broadly speaking, it appears that higher rates of drug overdose mortality are associated with markers of lower economic status (such as unemployment, poverty, reliance on public assistance income, use of public insurance) as well as weakened social support systems (such as non-family households, adults previously married). A key recommendation from this study is that these communities should be targeted for both addiction recovery services and preventative outreach and education, due their high vulnerability to this epidemic.

As new Census data becomes available this model can be used to generate updated predictions to guide intervention efforts.  But one of the shortcomings of the model is that it fails to predict some of the highest rates of drug mortality that have been seen in the US. It may be possible to improve the model by adding additional features.
