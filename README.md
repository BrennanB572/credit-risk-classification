# credit-risk-classification

Report:

I would not recommend using this machine learning model for credit risk classification due to the lack of success when predicting for high risk loans. While it might be successful in predicting a healthy loan, it would need both. If I were to do it differently, I'd take data from different data intervals and compare data week over week to see if the machine learning model improves on different dates then assess the performance being those time frames.

- Accuracy:
  Overall: 94%
- Precision:
  - Healthy Loan: 1.00 - Due to model overconfidence
  - High Risk Loan: 0 Due to underfitting
- Recall Score:
  - Healthy Loan: 0.97 or 97% accurate (overconfident)
  - High Risk Loan: 0% - Was unable to predict
