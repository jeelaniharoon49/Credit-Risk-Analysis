# Project Overview
This project predicts whether a borrower is likely to default on a loan using Machine Learning.
The model was trained on historical loan data and can classify borrowers as:
- Safe Loan
- High Risk of Default

# Business Problem
Banks and financial institutions need to identify risky borrowers before approving loans.
This project helps reduce financial losses by predicting default risk.
# Dataset Features
- Age
- Income
- Employment Length
- Loan Amount
- Interest Rate
- Loan Purpose
- Home Ownership
- Credit History Length
- Previous Defaults
Target Variable:
- loan_status
  - 0 = No Default
  - 1 = Default
## Machine Learning Model
Random Forest Classifier
## Results
Accuracy: 93%
### Confusion Matrix
<img width="840" height="687" alt="Screenshot 2026-06-11 195456" src="https://github.com/user-attachments/assets/54907dab-3709-4801-95c8-60d340b1f053" />

### Feature Importance
<img width="716" height="648" alt="Screenshot 2026-06-11 195450" src="https://github.com/user-attachments/assets/6c085efa-7c9c-45d1-beea-6e37a7ba5ca2" />
Top factors affecting loan default:
<img width="1131" height="561" alt="image" src="https://github.com/user-attachments/assets/8463522f-26e6-4d47-a3fb-d35282fbac17" />

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

## Author

Haroon Jeelani
