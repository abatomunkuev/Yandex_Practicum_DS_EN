# Analyzing borrowers’ risk of defaulting

[Jupyter Notebook viewer](https://nbviewer.jupyter.org/github/abatomunkuev/Yandex_Practicum_DS_EN/blob/main/bank_credit_score/bank_credit_score.ipynb)

This project shows: 
- ability of writing solid,structured Python code 
- ability of using existing utilities(libraries) for processing and analyzing data.
- analytical and data pre-processing skills

Project is mainly focused on data pre-processing. I showed my techniques in dealing with most common problems with data:
1. missing data
2. duplicate
3. abnormal values. 

Project also contains NLP part, where I show the algorithms that I have learned. Moreover, I have demonstrated my ability to effectively present the results to the team by visualizing and summarizing the insights that I have found through out the research.



## Data
Data input from the bank - statistics on customers' ability to pay. Each row of the table provides information about the client of the bank: the number of children in the family, employment history, age, education, marital status, gender, type of employment, whether customer had any debts, monthly income, and the purpose of obtaining credit.

|Column            |Description            |
 |:---------------|:------------------------|
|children        |number of childern in family                 |
|days_employed        |record of employment in days                |
|dob_years        |customer age in years               |
|education        |customer education level                 |
|education_id        |customer education level id                 |
|family_status        |family status                 |
|family_status_id        |family status id                 |
|gender        |gender                 |
|income_type        |type of employment                 |
|debt        |whether a customer was in debt                |
|total_income        |monthly total income  in Rubles             |
|purpose        |purpose to get a loan                 |

## Task

Customer - bank. We need to answer the question: whether the family status and number of children will have an impact on the fact of repayment of the loan on time. Conduct a research on data provided by the bank. The results of the research will be considerer in building a [**credit score**](https://en.wikipedia.org/wiki/Credit_score) model that assesses the potential borrower's ability to repay the loan to the bank.


## Libraries used
*pandas*
*numpy*
*matplotlib*
*seaborn*
*nltk*
*missingno*
