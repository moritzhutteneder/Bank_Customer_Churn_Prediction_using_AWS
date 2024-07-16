# Bank Customer Churn Prediction

#### This project aims to predict customer churn for a bank using machine learning models on AWS.

**Problem Description:**
The main objective is to maximize the bank’s revenue by minimizing unnecessary retention programs and marketing/acquisition costs for new customers by improving the churn model prediction.
![image](https://github.com/user-attachments/assets/c7b2bd33-9581-4dbb-bc01-d2745cb685ca)

**Solution Overview:**
By leveraging the power of AWS services and machine learning, this project predicts whether a customer will churn based on historical data. The solution includes data preprocessing, model training, hyperparameter tuning, deployment, and continuous monitoring.
![image](https://github.com/user-attachments/assets/ac7eb288-d38a-4f09-b8e2-1ddcb0477bed)

**Architecture:**
![image](https://github.com/user-attachments/assets/a44df8cc-67df-4fc7-8375-99542346c612)


**Key Features:**
- **Data Collection and Cleaning:** Historical customer data is collected, cleaned, and prepared for model training.
- **Feature Engineering:** Develop features indicative of churn, such as account activity patterns.
- **Churn Prediction:** Use XGBoost to predict whether a customer will churn.
- **Model Deployment:** Deploy the trained model using AWS SageMaker for real-time predictions.
- **Monitoring and Refinement:** Continuously monitor model performance and update as needed.

## How to Use
1. **AWS Notebook:** Run the code in the provided Jupyter Notebook on AWS.
2. **Data Connection:** The notebook connects to AWS S3 buckets where the data is stored.
3. **Data Exploration:** Explore and visualize customer data.
4. **Model Training:** Train the churn prediction model using the provided data.
5. **Prediction:** Use the trained model to predict customer churn.

**Results and Evaluation:**
![image](https://github.com/user-attachments/assets/5bea714c-2399-40a8-b1fd-97d9fc758164)


**Conclusion:**
- Implemented a predictive churn model using XGBoost with high accuracy.
- Streamlined retention programs and reduced unnecessary costs.
- Highlighted influential factors affecting customer churn.

## Requirements
- Jupyter Notebook
- AWS account with access to S3 buckets
- Necessary Python libraries (specified in the notebook)
