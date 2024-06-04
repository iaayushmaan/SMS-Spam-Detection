# SMS-Spam-Detection

In this repository, I have used the Multinomial Naive Bayes (MNB) classifier to detect spam messages. The choice of MNB was driven by its simple implementation, high accuracy, and efficient vector-based approach. To enhance my model’s performance, I evaluated several other classifiers, including:

- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN) Classifier
- Random Forest Classifier
- AdaBoost Classifier
- Bagging Classifier
- Extra Trees Classifier
- Gradient Boosting Classifier
- XGBoost Classifier
 
Among these, the Multinomial Naive Bayes demonstrated the highest precision. Additionally, I employed a Voting Classifier that combines predictions from SVC, MNB, and Extra Trees Classifier. Furthermore, I applied stacking by combining three estimators—SVM, Multinomial Naive Bayes, and Extra Trees—with a final RandomForestClassifier to improve overall performance.

![Screenshot 2024-06-04 213339](https://github.com/iaayushmaan/SMS-Spam-Detection/assets/116517217/c2ae7151-7ae6-4d7b-a288-5212a9533b70)



## Run Locally

1. Clone the project

```bash
  git clone https://github.com/iaayushmaan/SMS-Spam-Detection.git
```

2. Go to the project directory

```bash
  cd ./SMS-Spam-Detection
```

3. You are good to go!


## Authors

- [@iaayushmaan](https://www.github.com/iaayushmaan)

