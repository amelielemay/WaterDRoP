<p align="center">
<img width="562" height="135" alt="Screenshot 2025-10-03 at 11 39 10 AM" src="https://github.com/user-attachments/assets/35f835e0-37fc-4c1a-8bcf-8291c96c9bca" />
  
# Hydrolysis Rate Estimation
WaterDRoP is a machine learning model for predicting the rate of hydrolysis from chemical structure under environmentally relevant conditions (pH 7 and 25&deg;C).

## Using WaterDRoP
The tool is available from the notebook `WaterDRoP.ipynb`. It is intended to be run in Google Colab. The user can enter an individual SMILES string or a batch of multiple SMILES strings. The notebook will output the predicted hydrolysis half-life and display the training examples most similar to the entered structure.

## Training Dataset
The complete dataset of experimental hydrolysis rates used to train WaterDRoP is given in the file `dataset.xlsx`.

## Citation and Acknowledgments
Information on model development and performance is described in the publication [paper citation here]. Please cite the publication if you use WaterDRoP in your work. Artificial intelligence models from OpenAI (ChatGPT) and Google (Gemini) were used as coding aids in the development of WaterDRoP.

## Contact
Amélie Lemay, Massachusetts Institute of Technology
alemay@mit.edu
