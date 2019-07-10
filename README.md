# BreastCancer
The objective of these predictions is to assign patients to either a benign group that is noncancerous or a malignant group that is cancerous.


# Dataset
This breast cancer database was obtained from Dr. Wolberg’s office at the University of Wisconsin
Hospitals, Madison. Each record here contains values for different morphological and pathological
features of a tumor dissected from any given patient. The class column indicates whether the patient
has been characterized as the benign tumor or a malignant tumor.

Contains 700*11 rows and columns respectively  

Cancer.csv - should be in same directory as BreastCancer.py

# Resources
Spyder  
Pandas (library)  
Keras  (library)


# Classification Methods
Random Forrest  (RF)  
Support Vector Machine (SVM) 

# Confusion Matrix  
  |True Positive   False Positive |
  |False Negative  True Negative  |
  
  True Positive  = Answer (Benign)    - Predicted (Benign)  <br>
  False Positive = Answer (Malignant) - Predicted (Benign)<br>
  False Negative = Answer (Benign)    - Predicted (Malignant)<br>
  True Negative  = Answer (Malignant) - Predicted (Malignant)<br>
  
  # Support Vector Machine (SVM)
  True Positive  = 82   
  False Positive = 3  
  False Negative = 1  
  True Negative  = 54  
  
  SVM False Positive count i.e. predicted as having benign tumor but actually have malignant tumor = 3  
  
  # Random Forrest (RF)
   True Positive  = 83   
  False Positive = 2    
  False Negative = 2    
  True Negative  = 53  
  RF False Positive count i.e. predicted as having benign tumor but actually have malignant tumor = 2    
  
  # Accuracy
  SVM = 97.14 %
  Random Forrest = 97.14 %
 
 For having less number of false positive we should use random forrest.
 
 # Deep Learning Model
 Keras.ipynb and better_tumor_classifier.py are application of deep learning model on Breast Cancer dataset
  
  
