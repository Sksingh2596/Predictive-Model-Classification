📊 Customer Churn Prediction with Machine Learning

Welcome to the Customer Churn Prediction project! This repository demonstrates how to preprocess data, train, tune, and evaluate multiple machine learning models to predict customer churn using Python, scikit-learn, and pandas.

🚀 Project Overview

    Goal: Predict whether a customer will churn using various supervised learning algorithms.

    Tech Stack: Python, pandas, scikit-learn, matplotlib

    Workflow:

        Data Loading & Cleaning

        Feature Engineering & Scaling

        Model Training & Evaluation (Decision Tree, Logistic Regression, Random Forest)

        Hyperparameter Tuning (GridSearchCV)

        Visualization & Metrics


🛠️ Preprocessing

    Label Encoding: Transforms categorical columns (State, International plan, Voice mail plan, Churn) into numeric codes.

    Feature Scaling: Standardizes numeric features for improved model performance.

🤖 Models Trained

    Decision Tree

    Logistic Regression

    Random Forest

    Tuned Random Forest (via GridSearchCV)

Each model’s accuracy, precision, recall, and F1-score are displayed for comparison.

| Metric    | Decision Tree | Logistic Regression |
| --------- | --------------| ------------------- |
| Accuracy  |    *0.9145*   | *0.8651* | 
| Precision |    *0.6931*   | *0.5789* | 
| Recall    |    *0.7292*   | *0.2292* | 
| F1-Score  |    *0.7107*   | *0.3284* | 


📈 Results

After tuning the Random Forest, the confusion matrix below summarizes the prediction results:

    True Negatives: 564

    False Positives: 7

    False Negatives: 26

    True Positives: 70
    

# Key Metrics (Tuned Random Forest)
| Metric    | Value    |
| --------- | ---------|
| Accuracy  |  0.9505  |
| Precision | *0.9091* |
| Recall    | *0.7292* |
| F1-Score  | *0.8092* |


🌟 Try it Yourself!

    Replace the dataset with your own customer data.

    Adjust hyperparameters and experiment with new models.

    Visualize and compare your results with the provided confusion matrix and metrics.

📬 Feedback & Contributions

Pull requests and feedback are welcome! If you find this project helpful, give it a ⭐️.
