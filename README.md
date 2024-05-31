# Customer Churn Prediction


<img src="https://github.com/Vindyani1999/My-React-Projects/assets/145743416/7f6bca58-8409-4a32-847d-263ecf97d428" width="1000px" height="350px"/>

[![-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](https://github.com/BaseMax?tab=repositories)

This project aims to predict customer churn using machine learning techniques. Customer churn refers to the phenomenon where customers stop doing business with a company. Predicting churn can help businesses retain customers by addressing the reasons why customers might leave.

[![-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](https://github.com/BaseMax?tab=repositories)


## Dataset

The dataset contains 12 feature columns:

- **CustomerID**: A unique identifier for each customer
- **Age**: The age of the customer
- **Gender**: Gender of the customer
- **Tenure**: Duration in months for which a customer has been using the company's products or services
- **Usage Frequency**: Number of times that the customer has used the company’s services in the last month
- **Support Calls**: Number of calls that the customer has made to the customer support in the last month
- **Payment Delay**: Number of days that the customer has delayed their payment in the last month
- **Subscription Type**: Type of subscription the customer has chosen
- **Contract Length**: Duration of the contract that the customer has signed with the company
- **Total Spend**: Total amount of money the customer has spent on the company's products or services
- **Last Interaction**: Number of days since the last interaction that the customer had with the company
- **Churn**: Binary label indicating whether a customer has churned (1) or not (0)

## Project Workflow

1. **Install and Load the Dependencies**

2. **Load the Data**

3. **Analysing the Dataset**
    - 3.1 Initial Analysis
    - 3.2 Univariate Analysis
        - 3.2.1 Analysis using Categorical Features
        - 3.2.2 Analysing for Discrete Data
        - 3.2.3 Analysing for Continuous Data
    - 3.3 Multivariate Analysis
        - 3.3.1 Gender vs Churn Rate
        - 3.3.2 Payment Delays vs Churn Rate
        - 3.3.3 Usage Frequency vs Churn Rate
        - 3.3.4 Tenures vs Churn Rate
        - 3.3.5 Support Calls vs Churn Rate
        - 3.3.6 Customer Support vs Churn Rate
        - 3.3.7 Contract Length vs Churn Rate
        - 3.3.8 Relation Between Total Spend and Churn Rate
    - 3.4 Checking for Duplicates

4. **Outlier Detection**
    - Interquartile Range (IQR) Method

5. **Data Encoding**
    - One Hot Encoding

6. **Feature Scaling**
    - Normalization

7. **Data Balancing**
    - SMOTE Method

8. **Feature Selection**
    - 8.1 Correlation Matrix and Heat Map Visualization
    - 8.2 Mutual Information Feature Selection

9. **Train-Test Split**

10. **Baseline Models**

11. **K-Fold Cross Validation**
    - 11.1 K-Fold Cross Validation with Logistic Regression
    - 11.2 K-Fold Cross Validation with Naive Bayes
    - 11.3 K-Fold Cross Validation with k-Nearest Neighbor
    - 11.4 K-Fold Cross Validation with Decision Trees
    - 11.5 K-Fold Cross Validation with Random Forest

12. **Model Training**
    - 12.1 Model Training with Logistic Regression
    - 12.2 Model Training with Decision Tree
    - 12.3 Model Training with Random Forest

13. **Model Evaluating**
    - 13.1 Training Evaluation
    - 13.2 Testing Evaluation

14. **Hyperparameter Tuning**

15. **Saving the Best Model**

## Result

I have build an accurate model for customer chunk prediction and the trainer model can be found in the repository.



```bash
pip install -r requirements.txt
