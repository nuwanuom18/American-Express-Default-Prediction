# American-Express-Default-Prediction
### Predict if a customer will default in the future

The steps that I followed, briefly:

1. Understood the dataset. 
2. Reduced class imbalance. 
3. Handled null values - Used mode for some selected features and mean for some selected features
4. Encoded categorical features. Tried different methods (label, one hot but finally using an ordinal encoder)
5. Remove highly correlated features.
6. Scaling (tried min max scaler as well)
7. Created new features using Principal Component Analysis
8. Applied different ML models
9. Tuned ML models manually
10. Used ROC-AUC score and other evaluation metrics (mentioned above) to evaluate and select models.
