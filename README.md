Data and Code Availability for ML Model Development
“Machine Learning Models to Predict Optimal Design Conditions and Parameters for NExT Delivery”

The main directory includes the dataset used for training the models (34_feat_dataset), provided in (.xlsx) file format. The model.py/prelim_scr_retrain_bestmodels python nb contains a Python class (NESTED_CV_) that performs nested cross-validation. This class is used to train all machine learning models in the study, implementing a 10-fold nested cross-validation framework.

The outputs from the nested cross-validation are saved as pickle (.pkl) files in the (nested_CV_pkl) subdirectory. The optimal hyperparameter configuration for each model is stored as a (.pkl) file in the directory (trained_models2_34_feat_modelname_fly).

Additionally, each directory includes Python scripts for - preliminary model screening based on MAE for key outputs—transfection efficiency, cell viability, and MFI fold change and loading the best-trained model for prediction, Furthermore, all the codes used for creating figures presented in the study (Figure_x, Figure_x) are attached to improve reproducibility. 
