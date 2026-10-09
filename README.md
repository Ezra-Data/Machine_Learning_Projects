# Machine Learning Projects

This workspace contains 23 notebook-based machine learning projects. Each project folder includes a concise README with its problem, dataset details, approach, notebook-reported results, run instructions, and imported tools, plus a `requirements.txt`.

| Project | What it does | Best result | Link |
|---|---|---|---|
| Autism Classification | Predicts an autism screening class. | Random Forest CV accuracy 0.92; test accuracy 0.825. | [Project](./Autism_Prediction_Using_Dtree_Rfc_XGB) |
| Big Mart Sales Prediction | Predicts retail item sales. | XGBoost test R-squared 0.5156. | [Project](./Big_Mart_Sales_Prediction_with_XGB) |
| Breast Cancer Classification | Classifies tumors as malignant or benign. | Logistic Regression test accuracy 0.9298. | [Project](./Breast_Cancer_Classification_Prediction_Logistic_Regression) |
| Calories Burned Prediction | Estimates calories burned during exercise. | XGBoost test MAE 1.4834. | [Project](./Calories_Burnt_Prediction_Using_XGBR) |
| Car Price Prediction | Estimates used-car selling prices. | Linear Regression test R-squared 0.4776; MAE 315,159.34. | [Project](./Car_Price_Prediction_Using_Linear_Regression) |
| Credit Card Fraud Detection | Classifies transactions as legitimate or fraudulent. | Logistic Regression test accuracy 0.9289. | [Project](./Credit_Card_Fraud_Detection_Logistic_Regression) |
| Customer Churn Prediction | Predicts telecom customer churn. | Random Forest CV accuracy 0.84; evaluation accuracy 0.7793. | [Project](./Customer_Churn_Prediction_System_Dtree_Rfc_XGBC) |
| Customer Segmentation | Groups customers by income and spending score. | Five clusters selected by the elbow plot. | [Project](./Customer_Segmentation_Kmeans) |
| Diabetes Prediction | Predicts diabetes status from health measurements. | SVC test accuracy 0.7727. | [Project](./Diabetes_Prediction_SVM) |
| Fake News Classification | Classifies news as fake or real from author/title text. | Logistic Regression test accuracy 0.9791. | [Project](./Fake_News_Prediction_Using_Logistic_Regression) |
| Gold Price Prediction | Estimates gold prices from market indicators. | Random Forest test R-squared 0.9896. | [Project](./Gold_Price_Prediction_RandomForestRegressor) |
| Heart Disease Prediction | Classifies the heart-disease target. | Logistic Regression test accuracy 0.8197. | [Project](./Heart_Disease_Prediction_Logistci_Regression) |
| House Price Prediction | Estimates median house values. | Tuned HistGradientBoosting test RMSE 46,721.710; R-squared 0.833. | [Project](./House_price_prediction_Using_LR_Ri_L_Ra_HGBR) |
| Loan Status Prediction | Predicts loan approval. | SVC test accuracy 0.8333. | [Project](./Loan_Statues_prediction_SVM) |
| Medical Insurance Cost Prediction | Estimates medical insurance charges. | Linear Regression test R-squared 0.7447. | [Project](./Medical_Insurance_Prediction_LinearRegression) |
| Movie Recommendation | Recommends similar movie titles. | Five recommendations shown in the notebook example. | [Project](./Movie_recommendation_system) |
| Song Recommendation | Recommends songs from lyric similarity. | Five recommendations returned; no numeric evaluation metric reported. | [Project](./Music_Recommendation_System_using_Python_code_prep_2) |
| Parkinson's Disease Detection | Classifies Parkinson's status from voice measures. | SVC test accuracy 0.8718. | [Project](./Parkinson_s_Disease_Detection_SVM) |
| Rainfall Prediction | Predicts rainfall from weather measurements. | Random Forest test accuracy 0.8298. | [Project](./Rainfalll_Predictive_system_Random_Forest_Classifier) |
| Sonar Rock or Mine Classification | Classifies sonar measurements as rock or mine. | Logistic Regression test accuracy 0.7619. | [Project](./Sonar_Rock_Vs_Mine_Prediction_Logistic_Regression) |
| Spam Message Classification | Classifies messages as spam or ham. | Logistic Regression test accuracy 0.9668. | [Project](./Spam_Mail_Predictions_Logistic_Regression) |
| Titanic Survival Prediction | Predicts passenger survival. | Logistic Regression test accuracy 0.7821. | [Project](./Titanic_Survival_Prediction_Logistic_Regression) |
| Red Wine Quality Classification | Predicts a binary wine-quality label. | Random Forest test accuracy 0.925. | [Project](./Wine_Quality_Prediction_Random_Forest_Classifier) |

## Information not specified in the notebooks

Dataset source links are not specified for these projects:
- Autism_Prediction_Using_Dtree_Rfc_XGB
- Big_Mart_Sales_Prediction_with_XGB
- Breast_Cancer_Classification_Prediction_Logistic_Regression
- Calories_Burnt_Prediction_Using_XGBR
- Car_Price_Prediction_Using_Linear_Regression
- Credit_Card_Fraud_Detection_Logistic_Regression
- Customer_Churn_Prediction_System_Dtree_Rfc_XGBC
- Customer_Segmentation_Kmeans
- Diabetes_Prediction_SVM
- Fake_News_Prediction_Using_Logistic_Regression
- Gold_Price_Prediction_RandomForestRegressor
- Heart_Disease_Prediction_Logistci_Regression
- House_price_prediction_Using_LR_Ri_L_Ra_HGBR
- Loan_Statues_prediction_SVM
- Medical_Insurance_Prediction_LinearRegression
- Movie_recommendation_system
- Parkinson_s_Disease_Detection_SVM
- Rainfalll_Predictive_system_Random_Forest_Classifier
- Sonar_Rock_Vs_Mine_Prediction_Logistic_Regression
- Spam_Mail_Predictions_Logistic_Regression
- Titanic_Survival_Prediction_Logistic_Regression
- Wine_Quality_Prediction_Random_Forest_Classifier

No numeric model evaluation metric is reported for Customer_Segmentation_Kmeans, Movie_recommendation_system, or Music_Recommendation_System_using_Python_code_prep_2; their notebooks show cluster selection or example recommendations instead.
