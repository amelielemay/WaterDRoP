<p align="center">
<img width="624" height="131" alt="Screenshot 2026-02-24 at 8 45 03 AM" src="https://github.com/user-attachments/assets/6444617f-ed69-4ad7-a958-016b068be4b1" />

# Hydrolysis Rate Estimation
WaterDRoP is a machine learning model for predicting the rate of hydrolysis from chemical structure under environmentally relevant conditions (pH 7 and 25&deg;C).

## Using WaterDRoP
The tool is available from the notebook `WaterDRoP.ipynb`. It is intended to be run in Google Colab. The user can enter an individual SMILES string or a batch of multiple SMILES strings. The notebook will output the predicted hydrolysis half-life and display the training examples most similar to the entered structure.

## Training Dataset
The complete dataset of experimental hydrolysis rates used to train WaterDRoP is given in the file `dataset.xlsx`.

## Citation
Information on model development and performance is described in the publication [paper citation here].

## Acknowledgments
**Funding:** This work was supported by the MIT Office of Graduate Education and conducted using computing resources of the MIT Office of Research and Computing Data (ORCD).  
**AI Use:** Artificial intelligence models from OpenAI (ChatGPT) and Google (Gemini) were used as coding aids in the development of WaterDRoP.

## Contact
Amélie Lemay, Massachusetts Institute of Technology
alemay@mit.edu
