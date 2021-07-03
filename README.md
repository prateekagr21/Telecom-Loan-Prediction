# Telecom Sector Loan Prediction.

### USE CASE :
_Many donors, experts, and microfinance institutions (MFI) have become convinced that using mobile financial services (MFS) is more convenient and efficient, and less costly, than the traditional high-touch model for delivering microfinance services. MFS becomes especially useful when targeting the unbanked poor living in remote areas. The implementation of MFS, though, has been uneven with both significant challenges and successes._

_Today, microfinance is widely accepted as a poverty-reduction tool, representing 70 billion in outstanding loans and a global outreach of 200 million clients._

_One of our Client in Telecom collaborates with an MFI to provide micro-credit on mobile balances to be paid back in 5 days. The Consumer is believed to be delinquent if he deviates from the path of paying back the loaned amount within 5 days._


### WHAT I HAVE DONE IN THIS NOTEBOOK :
I have created a delinquency model which can predict in terms of a probability for each loan transaction,
whether the customer will be paying back the loaned amount within 5 days of insurance of loan.

![mfs](https://user-images.githubusercontent.com/73397927/124344043-c5f79000-dbed-11eb-86ba-b4a641db074f.jpg)

## For Solving this Usecase, What I have done is :
- Collected the data from kaggle and organized to form a meaningful dataset.
- Checked for null values and observed the data to form meaningful insights.
- Did Exploratory Data Analysis on the dataset.
- Visualizations were made by using Matplotlib and Seaborn Libraries.
- Finded correlation to form a Heatmap.

## And then I made a Model for the Prediction :
- Independent and Dependent Features.
- Did Train-Test split

## Fitted the Model by using :
-  RandomForestClassifier
-  Improved the accuracy by using Cross Validation Score.
-  SupportVectorMachine

## Checked the Prediction :
- Got the Accuracy and Rscore of the Model Prediction.
- Plotted Confusion Matrix.
- A Classificaion report is also shown.

`And at last , Completed it with a Conclusion Statement.`
