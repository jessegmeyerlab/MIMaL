# jupyter notebook descriptions

+ **compare-models.ipynb:** code to generate training/validation/test data from downloaded data inputs and then compare various models with different inputs
+ **extratrees-gridsearch.ipynb:** code to perform gridsearch with extratrees model
+ **yeast_multiomics_impute_SHAP.ipynb:** code to train extratrees models for each metabolite from proteomics data and calculate SHAP values across the entire dataset
+ **UMAP_Cluster.ipynb:** code to determine clustering from shap values using UMAP and OPTICS. Use generated clusters to create network linking original conditions.
+ **correlation.ipynb:** code to determine correlations between all proteins in imputed dataset and link them to eachother and to shap proteins in a network
+ **correlation-plots.ipynb:** code to generate correlation plots between metabolite fold changes and protein fold changes or SHAP values.
