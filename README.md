# credit-risk-classification

tutor and class activities help.

The purpose of this analysis is to measure the risk associated providing loans to risky and non risky applicants.  How accurately can we measure the credit worthiness of or borrowers.

      precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384


We see that the recall rate for Healthy loan applicants 99% and the precision is 100%
We see that the recall rate for Risky loan applicants is 91% and the precision is 85%

The accuracy overall for this model is 99% and as mentioned in the workbook, the concern is for the recall rate for the risky loan applicants being at 91% which is not low but still of concern.

In order to improve the mode, introducing Random Forest as an option because it will remove the initial bias in the data that has a lot more of healthy loan applicants within the data (number of data points) compared to high risk loan applicants.  We could also use pre processing where we oversample risk applicants by randomly duplicating the risky applicants to improve the data and see how this changes the model.
