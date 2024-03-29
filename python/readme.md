# jupyter notebook descriptions

+ **compare-models.ipynb:** code to generate training/validation/test data from downloaded data inputs and then compare various models with different inputs (~2h per fold: 3.40ghz Intel i7-3770)
+ **extratrees-gridsearch.ipynb:** code to perform gridsearch with extratrees model (~36h 3.40ghz Intel i7-3770)
+ **yeast_multiomics_impute_SHAP.ipynb:** code to train extratrees models for each metabolite from proteomics data and calculate SHAP values across the entire dataset (~9h training: 3.40ghz Intel i7-3770) 
+ **UMAP_Cluster.ipynb:** code to determine clustering from shap values using UMAP and OPTICS. Use generated clusters to create network linking original conditions. (~30 minutes per metabolite: 3.40ghz Intel i7-3770)
+ **correlation.ipynb:** code to determine correlations between all proteins in imputed dataset and link them to eachother and to shap proteins in a network (~2h: 3.40ghz Intel i7-3770)
+ **correlation-plots.ipynb:** code to generate correlation plots between metabolite fold changes and protein fold changes or SHAP values.
