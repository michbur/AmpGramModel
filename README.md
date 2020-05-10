# AmpGramModel - Data and model storage for AmpGram

This package is used only as model and data storage for [AmpGram](https://github.com/michbur/AmpGram) - package 
for prediction of antimicrobial peptides using n-gram encoding and random forests.

The **AmpGram_model.rda** file stores the core functionality of AmpGram: the stacked random forest model
and list of informative n-grams used for classification of peptides/proteins as AMPs or non-AMPs.
It is essential for proper use of AmpGram but needs to be stored in the external repository due to large
size of the model and CRAN file size limit. 

