# Fraud-Detection Model

### Dataset
https://www.kaggle.com/c/ieee-fraud-detection

## Description: 
Fraud Detection models:
- Autoencoder based on Semi-Supervised Learning.
- Random Forest based on Supervised Learning.

# Model details:
- Autoencoder:
  - Data: Just NON-FRAUD data
  - Architecture: Encoder and Decoder with 3 layer each
  - Loss function: L1 Loss
  - Optimization: Adam
  - Score Function: L1 Loss
  - Evaluation: AUC - Accuracy
  

- Random Forest:
  - Data: All Data
  - Evaluation: AUC
  
# Evaluation:
### Test results:
> Autoencoder:

> Detected Frauds:  16934
>
> Real Frauds:      20663
>
>
> Accuracy: 0.82


# Competition Result:
> Autoencoder: AUC = 0.79

> Random Forest: AUC = 0.88

