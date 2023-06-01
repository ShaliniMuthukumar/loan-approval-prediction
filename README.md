# loan-approval-prediction

Loan approval prediction is a machine learning task that involves training a model on a dataset of historical loan application data, and then using the trained model to predict whether a new loan application will be approved or not.

To implement this task, I gathered a dataset of historical loan application data, which would include features such as the applicant's credit score, income, employment status, loan amount, loan term, and other relevant information.

Then I need to preprocess and clean the data, splitting it into training and testing sets, and applying any necessary feature engineering techniques such as feature scaling or one-hot encoding.

Once the data is ready, we can train a logisti regression model model using the training set. The trained model can then be evaluated on the testing set to measure its performance in terms of metrics such as accuracy, precision, recall, and F1 score.

To deploy the model using Streamlit, we would first need to save the trained model as a file, and then write a Python script that loads the model, takes user input for the loan application features, and uses the model to make a prediction on whether the loan will be approved or not. This script can then be run using Streamlit, which provides a user-friendly interface for users to input their loan application information and view the prediction result.

Snapshot of the loan prediction model


<img width="628" alt="image" src="https://github.com/ShaliniMuthukumar/loan-approval-prediction/assets/106624891/6074bde5-67ba-4a10-b993-628322696e1e">
<img width="572" alt="image" src="https://github.com/ShaliniMuthukumar/loan-approval-prediction/assets/106624891/ca0184c1-d5ec-4915-accb-9583d909a502">
<img width="608" alt="image" src="https://github.com/ShaliniMuthukumar/loan-approval-prediction/assets/106624891/a7c6823b-3faa-4f4e-a4b8-26f083ebc11a">
