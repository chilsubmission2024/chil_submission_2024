# chil_submission_2024
Submission for CHIL 2024

This is the submission for CHIL 2024.
It includes CHIL_submission_file.ipynb and requirements.txt.
The jupyter notebook file contains the derivations, calculations, and experimentations for accounting measurement error of an imputed (and originally "unknown") confounder (ex: Smoking Status) in causal effects (specifically risk and odds ratio).
Additionally, pickle files such as varied error matrices used for bootstrapping are not included in this notebook, but the process of using them to measure the variance (+ "sensitivity") is still demonstrated.
It is important to note that due to privacy rules with MIMIC-III and Harvard's n2c2 2006 smoking dataset, it is not possible to show certain components of the processs (ex: data filtering, dataframe creatings, model traing, etc...).
However, some information about the dataframes are given within comments in the notebook, such as number of rows/cols and important feature names.