# Chest_X-Ray_Anomaly_Detection

This project aims to facilitate global health diagnosis via a large-scale screening system and practical tools & services. In this work, multiple datasets are explicit, including CheXpert(Chest eXpert), COVID, Pneumonia, and TB datasets. The main contribution of this work is to detect the 8 most significant pathology in the medical history of Chest X-Ray via a pathological hierarchical approach. The report discusses the use of multiple pre-trained models on the combined dataset, and further custom architectures have been trained from scratch to generate detection results. The results suggest the models built from transfer learning clearly supersedes the model trained from scratch. Separate datasets of COVID, Pneumonia, and TB are integrated into the CheXpert dataset. The entire work has been focused on improving the AUC score for detecting the following 8 classes- Atelectasis, Cardiomegaly, Consolidation, Edema, Pneumonia, Pleural Effusion, COVID, and TB. The proposed methods for label handling and AUC maximization achieve excellent performance with an AUC score of 0.8730 for classifying the above-mentioned 8 classes. The training pipeline and AUC maximization methods can be easily implemented to classify diseases in the Chest radiography dataset.

## Dataset

Chest X-rays datasets are taken from multiple sources:

1. [https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset](TB Dataset)
2. [https://github.com/ieee8023/covid-chestxray-dataset](COVID & Pneumonia dataset)
3. [https://stanfordmlgroup.github.io/competitions/chexpert/](CheXpert dataset)
