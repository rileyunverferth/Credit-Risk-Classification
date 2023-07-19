# Credit Risk Classification
## Supervised Machine Learning
### Overview

In this challenge we are training and evaluating a model based on loan risk. The model uses a dataset of historical lending activity from a peer-to-peer lending services company, which includes whether the loan was a healthy loan or a high-risk loan. The model trained on 75% of the data in order to learn trends, and then made predictions against the remaining 25% of the data. The accuracy of the predictions vs the test data is how we are able to see how well our model performed. The model was then used a second time on resampled training data in order to further see how well it performs. If the model performs well then we can use it to identify the creditworthiness of borrowers in the future, and determine if their loans will be healthy or high-risk. 

### Results
Using the model our model with the original data gave us the following results:
- Accuracy Score: 0.99
- Precision Score (Healthy Loans): 1.00
- Precision Score (High-Risk Loans): 0.85
- Recall Score (Healthy Loans): 0.99
- Recall Score (High-Risk Loans): 0.91

Using the model our model with the resampled data gave us the following results:
- Accuracy Score: 0.99
- Precision Score (Healthy Loans): 1.00
- Precision Score (High-Risk Loans): 0.84
- Recall Score (Healthy Loans): 0.99
- Recall Score (High-Risk Loans): 0.99

### Summary
Based on the results, our model performed very well. It was nearly perfect in acccuracy for both the original data and the resampled data. It was perfectly precise in predicting healthy loans for both data sets as well. Using the resampled data, the model performed slightly worse in precision for high-risk loans but 8% better in recall. Overall this is a very well performing model and I would recommend using it to determine loan safety. 
