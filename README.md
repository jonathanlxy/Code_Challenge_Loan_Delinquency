# [Code Challenge] Loan Delinquency Analysis & Prediction

This is my solution to an interview code challenge sent by a financial service company. The questions are listed below.

To view my solution (transformed into html page using knitr for better readability), please go to https://jonathanlxy.github.io/Code_Challenge_Loan_Delinquency/

__Tools/packages used__: 
- R (ggplot, data.table, dplyr, randomForest, rpart, rpart.plot, rattle, caTools)

----

Please spend some time familiarizing yourself with the data in “LoanData.csv”. This file contains some interesting information about portfolio performance as of November 1, 2012:


- __Days_delinquent_old__ represents how many payments a loan has missed as of November 1, 2012
- __Days_delinquent_new__ represents how many payments the same loan has missed as of December 1, 2012

The other fields are either categorical or continuous variable describing other things we knew about the loan as of November 1, 2012.

__Please address the following:__

1. Separate __days_delinquent_old__ and __days_delinquent_new__ into the following groups: (0, 1-5, 5-10, 10-30, 30-60, 60+). Create a transition matrix showing the probability of movement from one group to another. Create another transition matrix showing the probability of movement from one group to another, weighted by outstanding principal balance.

2. Tell me something interesting about a variable, model, or approach that allows you to distinguish loans whose delinquency is likely to worsen from those whose delinquency is likely to improve.

