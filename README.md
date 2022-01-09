# Suspicious_report_prediction
-   Author: Christopher Alexander

A data analysis project to the analyse the sales and productivity by prediciting a particular report to be Suspicious based 

## Buisness Objective:
- To analyse their sales and productivity by prediciting a particular report to be Suspicious
- The reports collected by the firm where each SalesPerson reports at a certain periodicity on which product was sold,how much quantity and totalAmount . 
- The past data also contains Suspicious column to determine the target .
- For statergic planning we would also want to segment salesPerson to 3 levels

## Machine Learning Objective:
The business objective expects us to create a fraud detecting system for each of their report based on their past data and grouping of salesPerson
- It is a Supervised learning - classifcation problem with Suspicious Column as our dependent variable.
- Segmentation of SalesPerson is Unsupervised Learning - clustering problem with respect to SalesPerson

The final code and analysis code can be found here [here](https://christopheralex.github.io/Suspicious_report_prediction/doc/Christopher_Alexander_2588_PHD.html)

## Approach
There were mutliple approaches tried in this process. 
For the classification problem, the methods and algorithms used are - 
1. Evaluation metric used - Recall
2. Feature engineering was performed after EDA on the given data to create new features.
3. Non linear features were created by using Autoencoders.
4. Several models were created with a combination of linear and non linear features to select best model.
5. Algorithms used were DecisionTree, RandomForest classifier.
6. The best model chosen was the RandomForest with Feature engineered features with overall recall 83% on class 1 (Suspicious)

For the clustering problem -
1. The kmeans clustering algorithm was used with a old and new features created.
2. The optimal cluster was found at 3 which was also the business objective.


## Requirements 
- Requires anaconda client with python 3.6 and other python packages. Please refer to requirements.txt
  - Some packages are running older versions which may not have support currently.

## License
The source code for the site is licensed under the MIT license, which you can find [here](https://github.com/christopheralex/Suspicious_report_prediction/blob/main/LICENSE).
