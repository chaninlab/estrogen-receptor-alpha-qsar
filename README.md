# Probing the origin of estrogen receptor alpha inhibition via large-scale QSAR study

This repository is comprised of 4 Jupyter notebooks constituting the entire workflow used in the construction of QSAR model for predicting the pIC50 value of estrogen receptor inhibition.

This repository includes:
* <span style="color:blue">*1_ERa_data_preparation.ipynb*</span>
  - Retrieves bioactivity data from ChEMBL database, curates and pre-process the data
* *2_ER_alpha_RO5.ipynb*
  - Performs Lipinski's rule-of-five analysis
* *3_ERa_descriptor_calculation.ipynb*
  - Computes fingerprint descriptors
* *4_ERa_multivariate_analysis.ipynb*
  - Performs multivariate analysis
* *requirements.txt*
  - Python environment output obtained via the *pip freeze* command
