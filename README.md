# Fraud-detection-system
Detecting Fraud Based On Unique Customer Behavior

Fraud detection is a critical challenge in financial transactions, requiring a balance between identifying fraudulent activities and minimizing false positives for genuine customers. This project implements a hybrid fraud detection system that combines traditional rule-based methods with machine learning techniques to identify fraudulent transactions effectively.

Unlike conventional fraud detection systems that rely solely on predefined rules, this system focuses on capturing unique customer behavior through feature engineering. By analyzing transaction patterns and behavioral deviations, the model improves its ability to distinguish between fraudulent and legitimate activities.

Key Features of the Project:

1. Hybrid Fraud Detection: Integrates rule-based methods with machine learning to improve detection accuracy.

2. Behavioral Analysis: Captures individual customer spending behavior and flags anomalies.

3. Feature Engineering: Creates advanced features such as average spending per week, transaction velocity, and deviation from normal spending patterns for better fraud detection.

4. Machine Learning Models: Train and evaluate multiple models, including Random Forest and Neural Network.

5. Imbalanced Data Handling: Use techniques like class weighting, decision threshold adjustment and cost-sensitive learning to improve fraud detection on rare fraud cases.

6. Performance Optimization: Tunes hyperparameters using Randomized Search and K-Fold Cross-Validation.

7. Real-Time Deployment: Deploy the trained model as an API (FastAPI) for real-time fraud detection.
