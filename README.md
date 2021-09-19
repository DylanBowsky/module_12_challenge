# module_12_challenge
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* For this notebook we are creating a new way to automate loan approvals. The purpose is to cut back on having underwriters having to spent countless hours going through applications and potentially losing customers. A bonus to this creates a more uniformed model for loan apps and guidlines. This data was on prexisting loans and the current status of the loan "healthy" or "unhealthy" 
* We wanted to find how many loans were in good and bad status so we used value counts. This also gives a clear picture to see how are sample size.
* The stages I went through for this project was a logistic Regression model along with using resampling. I used the standard model, fit, and predict to get our predicitons using the machine learning.
* The reason behind Logistic Regression is we are only using two outcomes healthy and healthy. Two outcomes are rare so as we continue we probably will need switch machine learning models. In this current data is not equal nor are they close, this is where resampling comes in affect and we use the over sampler.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * precision    recall  f1-score   support

        1.00      0.99      1.00     18765
        0.85      0.91      0.88       619
           Accuracy: .99



* Machine Learning Model 2:
  * precision    recall     f1-score   support

        1.00      0.99      1.00      18765
        0.84      0.99      0.91       619.
          accuracy                           0.99    

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
*  Model 2 performs better with a more accurate recall and f1 score for unhealthy, which I would think we would want to make sure we can predict this correctly. Since model 2 account for the over sampling and we see that are three times more values for healthy loans than unhealthy this almost a must for us.
* It is more important to predict unhealthy loans because as a loan provider we are taking the risk.healthy loans are nice to know in advance, but knowing if a loan won't be good before we even approve good be crucial in making a lower rate or more competitive pricing. Overall I would reccommend this model and project to keep going.

