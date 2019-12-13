<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Predicting conversion of a telemarketing campaign.
*Estefania Espinar*

*[Data Analytics, Barcelona, December 20th]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

The purpose of this project is to predict if a client will subscribe to a bank deposit or not after a telemarketing campaign. By doing this we will be able to decide which clients are more willing to subscribe and prioritaze them.

## Hypotheses / Questions
* What data/business/research/personal question you would like to answer?
* What is the context for the question and the possible scientific or business application?
* What are the hypotheses you would like to test in order to answer your question?  
Frame your hypothesis with statistical/data languages (i.e. define Null and Alternative Hypothesis). You can use formulas if you want but that is not required.

## Dataset

The data is from UCI Machine Learning Repository:  https://archive.ics.uci.edu/ml/datasets/bank+marketing
This dataset is public available for research. 

Citation:
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014

The dataset is related with direct marketing campaigns of a Portuguese banking institution. 

For this project, I'll be using the following datasets:

bank-additional-full.csv with 41188 rows and 20 columns with different features divided in 4 main categories:

* Personal data about the client: age, job, marital status, education, credit in default, housing loan, loan.
* Data related with the last contact of the current campaign: contact communication type, last contact month of year, last contact day of the week, last contact duration.
* Other attributes: number of contacts performed during this campaign and for this client, number of days that passed by after the client was last contacted from a previous campaign, number of contacts performed before this campaign and for this client, outcome of the previous marketing campaign.
* Social and economic context attribute: employment variation rate, consumer price index, consumer confidence index, euribor 3, number of employees.

The dataset also has a column with the output variable (desired target): - y - has the client subscribed a term deposit? (binary: 'yes','no')

bank-additional.csv with 10% of the examples (4119), randomly selected from the previous dataset, and the same number of columns.

## Cleaning
Describe your full process of data wrangling and cleaning. Document why you chose to fill missing values, extract outliers, or create the variables you did as well as your reasoning behind the process.

## Analysis
* Overview the general steps you went through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Include charts to demonstrate the effect of your work.
* If you used Machine Learning in your final project, describe your feature selection process.

## Model Training and Evaluation
*Include this section only if you chose to include ML in your project.*
* Describe how you trained your model, the results you obtained, and how you evaluated those results.

## Conclusion
* Summarize your results. What do they mean?
* What can you say about your hypotheses?
* Interpret your findings in terms of the questions you try to answer.

## Future Work
Address any questions you were unable to answer, or any next steps or future extensions to your project.

## Workflow
Outline the workflow you used in your project. What were the steps?
How did you test the accuracy of your analysis and/or machine learning algorithm?

## Organization
How did you organize your work? Did you use any tools like a trello or kanban board?

What does your repository look like? Explain your folder and file structure.

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project.


[Repository](https://github.com/)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
