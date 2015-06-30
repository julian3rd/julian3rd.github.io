---
layout: page
title: Model comparisons in R and Julia
permalink: http://julian3rd.github.io/model-comparison-r-julia/
---

# About
Comparison of statistical models from experimental data in R and Julia

## Comparing statistical models in R and Julia
When evaluating experimental data, implementing the statistical analyses in R is generally seen as the best way to go. Though other packages are available (SAS, JMP, SPSS, Stata, Python, etc.) R is open-source and used by a wide community of statisticians and others who need to use its power for statistical analysis. One issue that may arise when dealing with reproducible research is how you know if the models that were fit make sense and the results are consistent across environment. This is important, as not all statistical analysis packages are adept at fitting complex models, especially Linear Mixed Models (LMMs). In order to check the modeling performed, especially for complex calls, I recently decided to re-implement my analyses in other languages (e.g., the Python modules `Statsmodels` and `scikit-learn` when possible) but more often, using the Julia programming language.  

## Analysis demonstration
The analyses are demonstrated on several published datasets via the Jupyter/Ipython notebook. The notebooks canbe viewed either on GitHub or nbviewer.  

[GitHub page with links to source and nbviewer](http://julian3rd.github.io/model-comparison-r-julia/)  
