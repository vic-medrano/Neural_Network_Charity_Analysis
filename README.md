# Neural_Network_Charity_Analysis
## Overview
## Results
The purpose of this analysis is to look at previous organizations that have received funding from AlphabetSoup. Then AlphabetSoup would like to be able to make predictions to better understand where their funding would be most successful.
### Data Preprocessing
- The target variable for the model is whether or not the organization successfully utilized the funding from AlpabetSoup.
- The variables that are considered to be the features are the application type for the organization requesting funding, the affiliation, the classification, the organization, the ask amount, the use case, and the income amount, as well as ask amount.
- Variables that were neither targets nor features and that were removed from the data were EIN, name, special considerations, and status.
### Compiling, Training, and Evaluating the model
- There were two hidden layers. The first layer had 40 neurons while the second held 15. The number of neurons were chosen based off the typical rule of thumb that suggests the first layer of neurons should be about 2-3 times the number of features and the second should contain about a third of the neurons in the second layer.
- I was not able to achieve target model performance and continued to hit around a 53% accuracy rating.
- In an attempt to improve the model performance, extra columns that would not affect the outcome were removed. More specified bins were created to cluster the outliers further in an effort to allow the data to not be skewed so easily. The activation was also changed to tanh for the output layer
## Summary
The overall results of this deep learning model were not very successful or very accurate in classifying data. It could be recommended that an ensemble classifier may be more useful in this situation.
