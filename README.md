# iris-flower-classification
Machine learning model to classify Iris flower species
## Data Preprocessing
- The dataset was checked for missing values (No missing values were found).
- Feature scaling was performed using StandardScaler() to normalize the data.
- The categorical target variable (species) was label-encoded into numerical values.
## Model Selection
- We tested multiple classification models: 
  - Logistic Regression: **94% Accuracy**
  - Decision Tree: **95% Accuracy**
  - Random Forest: **97% Accuracy** (Final Model)
- Random Forest was chosen due to its higher accuracy and robustness.
## Model Evaluation
- **Accuracy:** 97%
- **Precision & Recall:**
- **Confusion Matrix & Feature Importance included in the notebook.**
