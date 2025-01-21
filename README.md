Welcome to the PBPK Models Repository, where we share physiologically-based pharmacokinetic (PBPK) codes developed to predict target site pharmacokinetics (PK) in various therapeutic contexts.


**Available PBPK Models**

This repository includes the following PBPK models:

1. Osimertinib PBPK Model in Lung Cancer:
A detailed PBPK model designed to predict the pharmacokinetics of osimertinib, a third-generation EGFR-TKI, in patients with lung cancer.

_Applications_: Understanding drug distribution, target-site exposure, and aiding in personalized therapy approaches.

2. [18F]F-DCFPyL and [177Lu]Lu-PSMA-617 PBPK Model in Prostate Cancer Patients:
A comprehensive PBPK model that simulates the biodistribution of [18F]F-DCFPyL (diagnostic tracer) and [177Lu]Lu-PSMA-617 (therapeutic agent) in patients with prostate cancer.

_Applications_: Prediction of target-site PK, dose optimization, and theranostic research.


**Structure**
The model is structure to include first all parameters that are used in the modeling. In case of small molecules the model PK predicitions are derived for each tissue, ordered as A.
Then physiological parameters are listed under B.
Finally the full model code including all differential equations per tissue compartment are included in C.


**How to use**
The models were created in R: 4.3.2. Rstudio development environment (version 2023.12.1 ) with the DeSolve package (version 1.40). 
Each model should be opened  run in the sequence as listed.
Required packages are described.

**Contributions**

Contributions to enhance or expand the models are welcome! If you have a PBPK model you would like to share or improvements to suggest:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request with a description of the updates.


**License**

This repository is shared under the Apache 2.0 License, allowing for use, modification, and distribution with appropriate credit to the authors.


**Contact**

For any questions or further information, please contact us at: i.bartelink@amsterdamumc.nl
