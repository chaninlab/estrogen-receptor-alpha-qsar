# Probing the origin of estrogen receptor alpha inhibition via large-scale QSAR study

This repository is comprised of the following folders and files that constitutes the entire workflow used in this study for the construction of QSAR models for predicting the pIC<sub>50</sub> value of estrogen receptor inhibition.

# Files
File names   |  Description
--- | ---
01_ER_alpha_preparation.ipynb | Retrieves bioactivity data from ChEMBL database, curates and pre-process the data
02_ER_alpha_RO5.ipynb | Performs Lipinski's rule-of-five analysis
03_Regression.ipynb | Constructs the initial QSAR models via random forest to obtain the set of top 20 descriptors
04_Regression_select_importance.ipynb | Constructs QSAR models using the top 20 descriptors
05_ER_alpha_preparation-test.ipynb | Prepares the input CSV file of the external set (< and > symbols in the bioactivity label)
06_External_test.ipynb | Applies the constructed QSAR model on the external set from 05_ER_alpha_preparation-test.ipynb.
07_Applicability_domain.ipynb | Performs applicability domain analysis via PCA bounding box approach
environment.yml | The conda environment that allows the replication of the Python environment (specific versions of installed packages) used in this study

# Folders
Folder names   |  Description
--- | ---
applicability_domain | Contain CSV files and output PDF files generated via 07_Applicability_domain.ipynb
Fingerprint | Contain CSV files of fingerprint descriptors calculated by the PaDEL software
model | Contain CSV files of bioactivity data obtained programmatically from the ChEMBL database
QSAR | Contain CSV files of fingerprint descriptors along with bioactivity data of all compounds used for QSAR model building
QSAR_select | Contain CSV files of the top 20 descriptors (from feature selection) used for building the final QSAR model
Result | Contain all results data
smiles | Contain SMILES data of all compounds used in this project
SubFiles | contain raw data files used in constructing plots
Train_Fp_normalized | contain fingerprint descriptors after normalized process

# Citing this work
If you use these codes and data, please cite the following paper:

Citing us |
--- |
Suvannang N, Preeyanon L, Malik AA, Schaduangrat N, Shoombuatong W, Worachartcheewan A, Tantimongcolwat T, Nantasenamat C. Probing the origin of estrogen receptor alpha inhibition via large-scale QSAR study. ***RSC Advances*** (2018) In Press. |
