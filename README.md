<p align="center">
  <img width="681" height="143" alt="Screenshot 2026-04-14 at 6 03 34 PM" src="https://github.com/user-attachments/assets/c8c4cf39-afb0-4c2b-978f-70b26b47a487" />


# Hydrolysis Rate Estimation
WaterDRoP is a machine learning model for predicting the rate of hydrolysis from chemical structure under environmentally relevant conditions (pH 7 and 25&deg;C).

## Using WaterDRoP
The tool is available from the notebook `WaterDRoP.ipynb`. It is intended to be run in Google Colab. The user can enter an individual SMILES string or a batch of multiple SMILES strings. The notebook will output the predicted hydrolysis half-life and display the training examples most similar to the entered structure.

## Training Dataset
The complete dataset of experimental hydrolysis rates used to train WaterDRoP is given in the file `dataset.xlsx`.
#### Update
June 2026: The dataset has been updated and the model retrained to reflect a correction to the carboxin datapoint. It was listed as unstable (half-life of 364.8 days) and has been corrected to stable (half-life > 1 year).

## Citation
Lemay, A.C.; Coley, C.W.; Plata, D.L. "Hydrolysis Reaction Rate Prediction Using Machine Learning: WaterDRoP." *Environ. Sci. Technol.* 2026, 60(17), 13088-13098. DOI: [10.1021/acs.est.5c16184](https://doi.org/10.1021/acs.est.5c16184)

## Acknowledgments
**Funding:** This work was supported by the MIT Office of Graduate Education and conducted using computing resources of the MIT Office of Research and Computing Data (ORCD).  
**AI Use:** Artificial intelligence models from OpenAI (ChatGPT), Anthropic (Claude), and Google (Gemini) were used as coding aids in the development of WaterDRoP.

## Contact
Amélie Lemay, Massachusetts Institute of Technology
alemay@mit.edu
