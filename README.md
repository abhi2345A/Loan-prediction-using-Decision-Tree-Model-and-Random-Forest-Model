# Loan-prediction-using-Decision-Tree-Model-and-Random-Forest-
In this i have analysed and visualized the loan dataset and converted its categorical feature like purpose of taking the loan to
the dummies and trained the dataset using Decision Tree Model and Random Forest model
then i have perform prediction on test data for both Decision tree model and Random forest model separately
In Random forest model i have no. of estimators(Trees) as 350
on comparison of classification report it was observed that Random forest did it better


Decision Tree:-
classification report-------------

          precision           recall  f1-score   support
          

          0                    0.86      0.82      0.84      2431
          1                    0.20      0.25      0.22       443

avg / total         0.75    
                    0.73      
                    0.74      
                    2874


Random Forest:-
classification report--------------

          precision           recall  f1-score   support
          

          0                   0.85      1.00      0.92      2431
          1                   0.47      0.02      0.03       443

avg / total         0.79     
                    0.85      
                    0.78      
                    2874
