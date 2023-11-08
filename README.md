# Heart-Disease-Predictions-Using-Supervised-Learning
Build a machine-learning model that can predict the likelihood of a person having a heart disease based on the given features.

Our mission is crystal clear: to build a machine-learning model that can predict the likelihood of a person having heart disease, using a range of critical features. The right and accurate data can indeed save lives, and we're committed to making a difference.

Let's dive into the key features of our dataset:
1. Age: Age in years.
2. Sex: Gender (1 = male, 0 = female).
3. Chest Pain Type: A crucial indicator of heart health.
4. Blood Pressure: Measured on admission to the hospital.
5. Cholesterol Level: An important serum marker.
6. Fasting Blood Sugar: >120 mg/dL (1 = true, 0 = false).
7. ECG Results: Providing insights into cardiac health.
8. Max Heart Rate: A significant parameter.
9. Exercise-Induced Angina: A yes/no indicator(1=yes; 0 = no)
10. ST Depression: Relative to rest.
11. ST Slope: A critical indicator during exercise.
14. Number of Major Vessels: An important diagnostic measure.
13. Thalassemia Type: Diverse types provide valuable insights.
14. Target: The presence of heart disease (1 = yes, 0 = no).

Data-driven decisions in healthcare are pivotal, and this project represents the epitome of leveraging data for the greater good. 
This ia predictive model that assist healthcare professionals in making timely and accurate decisions.

# Model Interpretation and Recommendation
In a project on Heart Disease Prediction using supervised learning, the performance of machine learning models can be assessed using four key measurement metrics: Accuracy Score, Precision Score, Recall, and ROC Score. Each of these metrics provides valuable insights into the model's performance. Let's interpret and explain the results for each of the models and then determine which one performed better and make a recommendation.

## Accuracy Score:
- Accuracy Score measures the overall correctness of predictions made by a model. It's the ratio of correctly predicted instances to the total instances in the dataset. A higher accuracy score is generally desirable.
- The Random Forest model achieved the highest accuracy score of 83.61%, closely followed by the Decision Tree and Logistic Regression models, both with 85.25%.
- The best-performing models in terms of accuracy are Random Forest, Decision Tree, and Logistic Regression.
## Precision Score:
- Precision Score evaluates the model's ability to make correct positive predictions. It is the ratio of true positives to the sum of true positives and false positives. Higher precision indicates fewer false positive predictions.
- The Decision Tree model achieved the highest precision score of 92.59%, followed by Naive Bayes at 90.0% and SGD Classifier at 87.88%.
- The best-performing model in terms of precision is the Decision Tree model.
## Recall:
- Recall, also known as sensitivity or true positive rate, measures the model's ability to correctly identify all positive instances. It is the ratio of true positives to the sum of true positives and false negatives. Higher recall indicates fewer false negatives.
- SGD Classifier achieved the highest recall of 90.62%, followed by Naive Bayes and Random Forest at 84.38%.
- The best-performing model in terms of recall is the SGD Classifier.
## ROC Score:
- The Receiver Operating Characteristic (ROC) score measures the trade-off between the true positive rate and the false positive rate for different classification thresholds. A higher ROC score indicates better discrimination performance.
- The SGD Classifier achieved the highest ROC score of 88.42%, followed by Naive Bayes at 87.02% and Random Forest at 83.57%.
- The best-performing model in terms of ROC score is the SGD Classifier.
## Summarry 
Based on the analysis of these metrics, the SGD Classifier consistently performed well across Precision, Recall, and ROC Score. It achieved the highest recall and a competitive ROC score. Therefore, the SGD Classifier appears to be the best-performing model for this heart disease prediction task.

## Recommendations:
Considering the SGD Classifier's balanced performance across multiple metrics, it is recommended to use the SGD Classifier as the final model for heart disease prediction in this project. However, hyperparameter tuning and further evaluation using cross-validation techniques may help optimize the model's performance further.
