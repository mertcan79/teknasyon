## Part A: SMS Spam Detection

The goal of this task is to classify SMS messages as **Spam** or **Not Spam**. We know this is an old school problem, but we would love to see your skills in text processing, feature engineering, model building on a multilingual dataset. (perspective and creativity too)

### Dataset
A dataset of SMS messages is provided. Each row contains:
- The SMS content.
- A label indicating whether the message is "Spam" or "Not Spam."

### What was done
- Train a classification model to predict the labels.
- Demonstrate how you handle preprocessing, feature extraction, and model evaluation.
- Feel free to use techniques like traditional ML (e.g., TF-IDF + SVM) or advanced methods (e.g., Transformer-based models, LLMs).
- Provide detailed documentation of your approach and any assumptions.

---

## Part B: Customer Churn Analysis

This task involves predicting customer churn based on their account and usage behavior. The dataset includes various metrics related to customer activity and account history.


### Dataset
A dataset containing customer-level metrics is provided. The goal is to predict whether a customer will churn in the near future.  
Columns in the dataset include (but are not limited to):
- `user_account_id`: Unique customer identifier.
- `user_lifetime`: Number of days since account creation.
- `user_spendings`: Total spending in the last month.
- `calls_outgoing_count`: Total number of outgoing calls in the last month.
- `user_no_outgoing_activity_in_days`: Number of consecutive days with no outgoing activity.
- `reloads_sum`: Total amount reloaded into the account in the last month.

### What was done
- Develop a predictive model for churn classification.
- Document your data exploration, feature engineering, and modeling steps.
- Highlight any assumptions you made about the dataset and its context.
