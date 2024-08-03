# neural-network-challenge-1

## Background
You work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. Your team has asked you to create a model to predict student loan repayment.

The business team has given you a CSV file that contains information about previous student loan recipients. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.


**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**
The below data attributes are required to build a recommendation system to recommend student loan options for students.

`Personal Information:`
- Age
- marital status 
- dependents
`Reason:` Relevant for tailoring loans to individual circumstances. 

`Educational Information:`
- Current educational level
- field of study
- school
`Reason:` Important for matching specific loan programs. 

`Financial Information:`
- Household income
- credit score
- existing debts
- financial aid received
`Reason:` Essential for determining loan eligibility and repayment capacity. 

`Loan Preferences and Constraints:`
- Loan amount needed
- repayment term preferences
- interest rate type
- repayment deferment
`Reason:` Ensures recommendations align with student preferences.

`Career Aspirations and Job Market Data:`
- Expected salary post-graduation
- industry growth trends
- Helps assess future repayment ability
`Reason:` Ensures recommendations align with student preferences.

`Geographical Information:`
- State of residence
- cost of living
`Reason:` Relevant for state-specific loans and financial needs.


**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

```
Context-based filtering is suitable because it:
Utilizes a comprehensive set of individual-specific data points to generate personalized recommendations. Tailors loan options based on the student's unique circumstances and preferences, rather than relying on patterns of similar users (collaborative filtering) or solely on loan features (content-based filtering). Ensures that the recommended loans are relevant and manageable within the student’s personal, educational, financial, and geographical context
```

**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**
```
1) Handling sensitive personal and financial information securely
2) Predicting future earnings accurately 
3) eliminating or handling system bias based on ndividual attrbutes 
```