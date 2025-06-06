# Accuracy Score in Machine Learning
### App Link 
- https://accuracy-score.streamlit.app/
---
### What is Accuracy Score?
- Accuracy Score measures how many predictions a machine learning model gets **correct** compared to the total predictions made.
---
### Formula for Accuracy Score
Accuracy Score = (Correct Predictions) / (Total Predictions)

Or, in classification problems:

Accuracy Score = (True Positives + True Negatives) / (True Positives + True Negatives + False Positives + False Negatives)

Where:
- **True Positives (TP):** Correctly predicted positive cases.
- **True Negatives (TN):** Correctly predicted negative cases.
- **False Positives (FP):** Incorrectly predicted positive cases.
- **False Negatives (FN):** Incorrectly predicted negative cases.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
---
### Example Problem
- Checking Accuracy of a Model
- We have actual results (**`y_true`**) and predicted results (**`y_pred`**)
---
### How it Works
* The model **compares predictions** with actual values.
* It **counts the correct predictions**.
* It **divides correct predictions by total predictions**.
* The result is the **Accuracy Score**, which measures overall correctness.
* Accuracy Score **works best when data is balanced**. If one class dominates, accuracy **may not be a good metric**.
---
