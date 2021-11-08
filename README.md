# Supervised machine learning for the assessment of Chronic Kidney Disease advancement 

This repository has been created has complement of the manuscript ```Ventrella P, Delgrossi G, Ferrario G, Righetti M, Masseroli M. "Supervised machine learning for the assessment of Chronic Kidney Disease advancement". Computer Methods and Programs in Biomedicine, 2021; 209: 106329. DOI: [10.1016/j.cmpb.2021.106329] (https://doi.org/10.1016/j.cmpb.2021.106329)```.

The repository contains:
- [**training.csv**](https://github.com/Piervipv/CKD_advancement_assessment/blob/main/training.csv): training dataset used for training and comparing through cross-validation the different algorithms considered and building the computational models
- [**test.csv**](https://github.com/Piervipv/CKD_advancement_assessment/blob/main/test.csv): test dataset to asses the performance of the models
- [**Notebook.ipynb**](https://github.com/Piervipv/CKD_advancement_assessment/blob/main/Notebook.ipynb): Notebook containing the Python code for computing an overview of the dataset and for training and testing the proposed computational models. The Notebook also contains the code for uploading and using the following pre-trained models:
- [**clf_binary.joblib**](https://github.com/Piervipv/CKD_advancement_assessment/blob/main/clf_binary.joblib): the pretrained ExtremelyRandomizedTrees model for the binary classification problem
- [**clf_DT_binary.joblib**](https://github.com/DEIB-GECO/CKD_advancement_assessment/blob/main/clf_DT_binary): a pretrained binary DecisionTree classifier, useful for comparing the performance with respect to the ExtremelyRandomizedTrees classifier
- [**clf_RF_binary.joblib**](https://github.com/DEIB-GECO/CKD_advancement_assessment/blob/main/clf_RF_binary): a pretrained binary RandomForest classifier, useful for comparing the performance with respect to the ExtremelyRandomizedTrees classifier
- [**clf_3Classes.joblib**](https://github.com/Piervipv/CKD_advancement_assessment/blob/main/clf_3Classes.joblib): the pretrained ExtremelyRandomizedTrees model for the 3-classes classification problem
- [**clf_DT_3Classes.joblib**](https://github.com/DEIB-GECO/CKD_advancement_assessment/blob/main/clf_DT_3Classes): a pretrained 3-classes DecisionTree classifier
- [**clf_RF_3Classes.joblib**](https://github.com/DEIB-GECO/CKD_advancement_assessment/blob/main/clf_RF_3Classes): a pretrained 3-classes RandomForest classifier
- [**clf_4Classes.joblib**](https://github.com/Piervipv/CKD_advancement_assessment/blob/main/clf_4Classes.joblib): the pretrained ExtremelyRandomizedTrees model for the 4-classes classification problem
- [**clf_DT_4Classes.joblib**](https://github.com/DEIB-GECO/CKD_advancement_assessment/blob/main/clf_DT_4Classes): a pretrained 4-classes DecisionTree classifier
- [**clf_RF_4Classes.joblib**](https://github.com/DEIB-GECO/CKD_advancement_assessment/blob/main/clf_RF_4Classes): a pretrained 4-classes RandomForest classifier

For details about the conducted study, please check the original manuscript.

