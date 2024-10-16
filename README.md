# Pain-Classification-from-Physiological-Signals-Using-Hand-Crafted-Features
This project focuses on developing a machine learning-based system that classifies pain from physiological data collected from wearable devices. The data consists of four types: Diastolic BP, Systolic BP, EDA, and Respiration, collected from 60 subjects. For each data type, features such as mean, variance, min, and max are extracted, resulting in 16 features when all data types are fused.

The system utilizes a classifier (e.g., SVM, Random Forest, etc.) to distinguish between pain and no-pain classes through a 10-fold cross-validation approach, ensuring subject-level validation. The output includes the confusion matrix, classification accuracy, precision, and recall averaged over all folds.

Key experimental goals include:

Investigating which physiological signals are most indicative of pain.
Comparing the performance of individual signals and fused signals.
Analyzing the variability of features and signals through visual plots.
