# Supervised machine learning for the assessment of Chronic Kidney Disease advancement 

This repository has been created has complement of the manuscript ```Ventrella P, Delgrossi G, Ferrario G, Righetti M, Masseroli M. "Supervised machine learning for the assessment of Chronic Kidney Disease advancement", 2021```.

The repository contains:
- training.csv: training dataset used for training and comparing through cross-validation the different algorithms considered and building the computational model
- test.csv: test dataset to asses the performance of the model
- Notebook.ipynb: Notebook containing the Python code for computing an overview of the dataset and for training and testing the proposed computational model. The Notebook also contains the code for uploading and using the pre-trained models.
- clf_binary.joblib: the pretrained ExtremelyRandomizedTrees model for the binary classification problem.
- clf_3Classes.joblib: the pretrained ExtremelyRandomizedTrees model for the 3-classes classification problem.
- clf_4Classes.joblib: the pretrained ExtremelyRandomizedTrees model for the 4-classes classification problem.

For details about the conducted study, please check the original manuscript.

