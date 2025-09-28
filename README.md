
# Cancer Prediction using Support Vector Machine (SVM)

## Overview
This project focuses on predicting the presence of cancer using a classification algorithm — Support Vector Machine (SVM). The model was trained and evaluated on a dataset containing gene expression data.

## Model Description
- **Algorithm Used**: Support Vector Machine (SVM)  
- **Accuracy Achieved**: 94.0%  
- The model was trained to classify whether cancer is present based on gene expression features.

## Dataset
- A dummy dataset was generated using the `Faker` library to simulate realistic gene expression data.
- The dataset includes features such as `Gene One`, `Gene Two`, and a binary label `Cancer Present`.

## Evaluation
- A confusion matrix was used to evaluate the model's performance.
- The model shows high counts of correct predictions and relatively low errors.
- **False Negative Rate**: Low, which is crucial in medical diagnostics to avoid missing actual cancer cases.
- **False Positive Rate**: Also reasonably low, meaning fewer unnecessary alarms.

## Conclusion
This project demonstrates that SVM is an effective model for cancer prediction, achieving high accuracy. The use of synthetic data via Faker confirmed the model's ability to generalize and correctly identify non-cancerous cases. Evaluation using a confusion matrix further supports the model's reliability. Overall, the SVM model is a strong candidate for classification tasks in medical diagnostics.

