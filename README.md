# Predicting Pregnancy Status Using the Dataset for Fetus Framework

This project builds a multimodal machine learning pipeline that predicts pregnancy status using ultrasound images together with clinical tabular data. The workflow comprises image preprocessing, balanced training, model comparison for both data types, late fusion of predictions, and clear explanations with SHAP and Grad-CAM.

---

## Objectives

* Cleaning and preparing ultrasound images with denoising, segmentation, cropping, and resizing
* Preparing tabular features with encoding, scaling, and quality checks
* Handling class imbalance with SMOTE
* Training image models using CNN and CNN-LSTM
* Training tabular models using Logistic Regression, Random Forest, and SVM
* Combining predictions with a late-fusion voting approach
* Explaining predictions using SHAP for tabular features and Grad-CAM for images
* Evaluating results with accuracy, precision, recall, F1, confusion matrices, ROC curves, and cross-validation

---

## Files

* `fetus_framework_final_code_omer.ipynb`  
  Final Colab notebook with preprocessing, training, evaluation, Grad-CAM, and SHAP
* `Predicting Pregnancy Status Using the Dataset for Fetus Framework.pdf`  
  Final report (PDF) with methods, figures, results, and APA references
  
---

## Data Sources

* Cui, C., & Dong, F. (2022). *Dataset for Fetus Framework* [Data set]. Mendeley Data. https://data.mendeley.com/datasets/n2rbrb9t4f/1
* Clinical background sources are listed in the PDF report’s References section

---

## Tools & Libraries

* Python (Colab / Jupyter Notebook)
* pandas, numpy, seaborn, matplotlib
* scikit-learn, imblearn (SMOTE)
* TensorFlow / Keras
* OpenCV, PIL
* SHAP, Grad-CAM

---

## Author

**Omer Gorgun**  
M.S. in Data Science | M.S. in Business Analytics | B.S. in Economics

---

## Notes

This project shows practical experience in combining medical images with clinical data, training models that are accurate and interpretable, and presenting results that support real-world decision making.
Through using ensemble modeling, deep learning, and medical imaging, the findings can be improved to detect and classify cases in the domains of Recurrent Implantation Failure (RIF), Recurrent Pregnancy Loss (RPL), both, or none (normal). 
