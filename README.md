# credit-risk-classification Analysis

This report details the construction and evaluation of a predictive model aimed at identifying potential credit risks among loan applicants. This capability is critical for financial institutions that aim to balance risk management with the need to extend credit to qualified applicants.

The data for this analysis consisted of several financial attributes related to borrowers, which formed the basis for predicting whether a loan would likely be repaid or default. The target variable, loan_status, was categorized into "healthy" (0) and "high-risk" (1). An initial exploration of this variable revealed a disproportionate number of healthy loans compared to high-risk ones, setting the stage for a potentially challenging classification task.

*The analytical process included:*

1. Preparing the dataset by addressing missing values and encoding categorical variables.
2. Dividing the data into a training set and a test set to allow for an unbiased evaluation of the model.
3. Choosing logistic regression as the predictive model, a standard approach for binary classification tasks.
4. Assessing model performance using comprehensive metrics, including accuracy, precision, recall, and the F1-score.
5. Evaluation of Model Performance
6. The following points summarize the key outcomes from the logistic regression model applied in this study:

*Logistic Regression Model Performance:*
Overall Accuracy: The model reached an impressive 99% accuracy, effectively predicting the loan status in nearly all cases.
Precision by Class:
For "healthy" loans: Achieved a precision of 100%, with every prediction of loan healthiness being correct.
For "high-risk" loans: Recorded a precision of 86%, indicating a strong ability to correctly label high-risk loans, albeit with some room for improvement.
Recall by Class:
For "healthy" loans: Demonstrated a recall of 100%, successfully identifying every actual healthy loan.
For "high-risk" loans: Achieved a recall of 91%, effectively identifying the majority of actual high-risk loans.

*Conclusion*
The logistic regression model proved to be highly effective, especially in accurately identifying healthy loans. Its robust performance in recognizing high-risk loans, although slightly less perfect, still suggests a strong predictive capability that is crucial for risk management in financial operations.

Given its strong performance across various metrics, this model is recommended for deployment in environments where precision in identifying loan repayment capabilities is paramount. Its high level of accuracy in both identifying genuine cases of creditworthiness and flagging potential defaults makes it a valuable tool for financial institutions. Nevertheless, to maintain its effectiveness, it’s advisable to continually refine the model by training it with new data, thereby ensuring it adapts to evolving economic conditions and borrower behaviors.

Reference:
I used the lecture notes and ChatGPT
