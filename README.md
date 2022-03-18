# Unit-11---Risky-Business

In this project we used machine learning to model credit risks. The two types models we used were resampling and ensemble learning methods.

The below are our findings after performing our analysis. 

## Resample Learning:

Which model had the best balanced accuracy score?

The Logistic Regression model using the SMOTE Oversampler had the best balanced accuracy score with a score of 0.9948

Which model had the best recall score?

Both the Oversampled and Undersampled models had the same recall score of 0.99

Which model had the best geometric mean score?

Both the Logistic Regression model using the SMOTE Oversampler and the SMOTEENN combination sampler had best geometric mean scores with scores at 0.99

## Ensemble Techniques:
 
Which model had the best balanced accuracy score?

The random undersampling model had the better balance accuracy score (0.8143740911743185 compared to 0.7887512850910909).

Which model had the best recall score?

The balanced random forest classifier had the better recall score (0.87 compared to 0.80).

Which model had the best geometric mean score?

The random undersampling model had the better geometric score (0.81 compared to 0.78).

What are the top three features?

The top three features are total_rec_prncp, total_rec_int, total_pymnt_inv.
