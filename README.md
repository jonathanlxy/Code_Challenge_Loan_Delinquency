# [Code Challenge] Loan Delinquency Analysis & Prediction

This is my solution to an interview code challenge sent by a financial service company. The questions are listed below.

----

Please spend some time familiarizing yourself with the data in “LoanData.csv”. This file contains some interesting information about portfolio performance as of November 1, 2012:


- __Days_delinquent_old__ represents how many payments a loan has missed as of November 1, 2012
- __Days_delinquent_new__ represents how many payments the same loan has missed as of December 1, 2012
The other fields are either categorical or continuous variable describing other things we knew about the loan as of November 1, 2012.
Please address the following:
1)    Separate days_delinquent_old and days_delinquent_new into the following groups: (0, 1-5, 5-10, 10-30, 30-60, 60+). Create a transition matrix showing the probability of movement from one group to another. Create another transition matrix showing the probability of movement from one group to another, weighted by outstanding principal balance.
2)    Tell me something interesting about a variable, model, or approach that allows you to distinguish loans whose delinquency is likely to worsen from those whose delinquency is likely to improve.

