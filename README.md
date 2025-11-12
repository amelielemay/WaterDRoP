<p align="center">
<img width="616" height="127" alt="Screenshot 2025-11-09 at 12 12 21 PM" src="https://github.com/user-attachments/assets/ef926da7-85d2-490a-80c2-bf8ed18ac6fd" />



# Hydrolysis Rate Estimation
WaterDRoP is a machine learning model for predicting the rate of hydrolysis from chemical structure under environmentally relevant conditions (pH 7 and 25&deg;C).

## Using WaterDRoP
The tool is available from the notebook `WaterDRoP.ipynb`. It is intended to be run in Google Colab. The user can enter an individual SMILES string or a batch of multiple SMILES strings. The notebook will output the predicted hydrolysis half-life and display the training examples most similar to the entered structure.

## Training Dataset
The complete dataset of experimental hydrolysis rates used to train WaterDRoP is given in the file `dataset.xlsx`.

## Citation and Acknowledgments
Information on model development and performance is described in the publication [paper citation here].
This work was supported by the MIT Office of Graduate Education and conducted using computing resources from the MIT Office of Research and Computing Data (ORCD). Artificial intelligence models from OpenAI (ChatGPT) and Google (Gemini) were used as coding aids in the development of WaterDRoP.

## Contact
Amélie Lemay, Massachusetts Institute of Technology
alemay@mit.edu
