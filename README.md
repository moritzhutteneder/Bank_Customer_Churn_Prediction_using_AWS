# Bank Customer Churn Prediction

#### This project aims to predict customer churn for a bank using machine learning models on AWS.

**Problem Description:**
The main objective is to maximize the bank’s revenue by minimizing unnecessary retention programs and marketing/acquisition costs for new customers by improving the churn model prediction.

**Solution Overview:**
By leveraging the power of AWS services and machine learning, this project predicts whether a customer will churn based on historical data. The solution includes data preprocessing, model training, hyperparameter tuning, deployment, and continuous monitoring.

**Key Features:**
- **Data Collection and Cleaning:** Historical customer data is collected, cleaned, and prepared for model training.
- **Feature Engineering:** Develop features indicative of churn, such as account activity patterns.
- **Churn Prediction:** Use XGBoost to predict whether a customer will churn.
- **Model Deployment:** Deploy the trained model using AWS SageMaker for real-time predictions.
- **Monitoring and Refinement:** Continuously monitor model performance and update as needed.

**How to Use:**
1. Clone the repository: `git clone https://github.com/yourusername/bank_customer_churn_prediction.git`
2. Navigate to the project directory: `cd bank_customer_churn_prediction`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the data processing scripts in `src/data_processing.py`.
5. Train the model using `src/model_training.py`.
6. Deploy the model using `src/deployment.py`.

**Results and Evaluation:**
- **Accuracy:** The model effectively classifies churn and non-churn cases.
- **Precision:** High precision indicates reliable churn predictions.
- **F1 Score:** Suggests enhancing recall for better churn identification.
- **AUC:** Train AUC: 0.9084, Validation AUC: 0.8537

**Conclusion:**
- Implemented a predictive churn model using XGBoost with high accuracy.
- Streamlined retention programs and reduced unnecessary costs.
- Highlighted influential factors affecting customer churn.

