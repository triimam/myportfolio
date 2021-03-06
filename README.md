# Data Science Portfolio


This is my repository for my projects.
The projects is written in Python (Jupyter Notebook). Click on the projects to see full analysis and code.

Please contact me on [Linkedin](https://www.linkedin.com/in/triimamwicaksono)

## Projects:

###  [Correlation Analysis between Tesla, Bitcoin, and Dogecoin Price](https://github.com/triimam/myportfolio/blob/c88894b145f69f9c3f3fa949df4c57062cd5df2e/Correlation%20Analysis%20between%20Tesla,%20Bitcoin,%20and%20Dogecoin/Notebook%20-%20Correlation%20Analysis.ipynb)
* Gathering data from yahoo finance
* Using pearson correlation and p-value to analyze between each variable
* Results, there is a significant correlation between TSLA and Bitcoin price, meanwhile the Dogecoin also moderately corelate to TSLA price
* **Keywords**(Python, Correlation Analysis, Bitcoin, Cryptocurrency)

<img src="Correlation Analysis between Tesla, Bitcoin, and Dogecoin/TSLA.png" width="500">

<img src="Correlation Analysis between Tesla, Bitcoin, and Dogecoin/Bitcoin.png" width="500">

<img src="Correlation Analysis between Tesla, Bitcoin, and Dogecoin/Dogecoin.png" width="500">


<img src="Correlation Analysis between Tesla, Bitcoin, and Dogecoin/heatmap.png" width="500">


###  [Loan Status Classification](https://github.com/triimam/myportfolio/blob/main/Loan%20Status%20Classfication/Loan%20Status%20Classification.ipynb)
* Gathering data from IBM
* Comparing several classifications method (KNN, Decision Tree, SVM, Logistics Regression)

### About the Dataset
This dataset is about past loans. The **Loan_train.csv** data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it???s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |


### Data Visualization
<img src="Loan Status Classfication/Principal Distribution by Gender and Age.png" width="500">

<img src="Loan Status Classfication/Principal Distribution by Gender and Principal.png" width="500">

### Results:
| Algorithm          | Jaccard | F1-score | LogLoss |
| ------------------ | ------- | -------- | ------- |
| KNN                | 0.72    | 0.73     | NA      |
| Decision Tree      | 0.74    | 0.63     | NA      |
| SVM                | 0.75    | 0.65     | NA      |
| LogisticRegression | 0.72    | 0.65     | 0.58    |
