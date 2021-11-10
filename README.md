# Classification Homework

## Credit Risk Resampling Techniques (Jupyter Notebook 1)

### Final Questions

Which model had the best balanced accuracy score?

* The SMOTEEN model has the best balanced accuracy score because it is closest to 1.0

2. Which model had the best recall score?

* Each model has a total recall score of 0.99 which we are happy to see because a score of 0.50 and above  is considered a good score.

3. Which model had the best geometric mean score?

* The Naive Random Oversampling, SMOTE Oversampling, and the Combination (Over and Under) Sampling all produced the highest geometric mean score of 0.99

## Ensemble Learning (Jupyter Notebook 2)

### Final Questions

1. Which model had the best balanced accuracy score?

* The Easy Ensemble Classifier has the best balanced accuracy score of 0.93 as it is closer to 1. 

2. Which model had the best recall score?

* The Easy Ensemble Classifier model has the best recall score of 0.94.

3. Which model had the best geometric mean score?

* The Easy Ensemble Classifier model has the best geometric mean score of 0.93.

4. What are the top three features?

* The top three features are: 
    * total principal received (tot_rec_prncp)
    * total interest received (total_rec_int)
    * total payment invoiced (tot_pymnt_inv)

* In conclusion, the most important feature for predicting loan risk appears to be the portion of the loan payment that represents the principal payment. This is expected because the borrower pays down more of the principal (original loan amount) therefore decreasing the lender's potential loss on the original loan. As the potential loss decreases, credit risk also decreases.
