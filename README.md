# Real Estate Value Estimator

This project aims to build a machine learning pipeline that preprocesses customer data, engineers features, trains multiple classification models, and evaluates their performance using metrics such as ROC-AUC and F1-score. It predicts the likelihood of successful transactions based on customer engagement and payment history.

---

## Features

- Preprocessing of customer data, including handling missing values, encoding categorical variables, and normalizing numerical features.
- Feature engineering to derive meaningful insights (e.g., session duration, payment failures, engagement score).
- Implementation of three models: Logistic Regression, Random Forest, and Gradient Boosting.
- Evaluation using metrics such as ROC-AUC and F1-score.
- Detailed classification reports for each model.

---

## Dataset

The dataset consists of customer records with the following columns:

| Column               | Description                                |
|----------------------|--------------------------------------------|
| `customer_id`        | Unique identifier for each customer       |
| `total_payments`     | Total number of payment attempts          |
| `successful_payments`| Number of successful payment attempts     |
| `session_start_time` | Start time of the session (minutes)       |
| `session_end_time`   | End time of the session (minutes)         |
| `time_on_site`       | Active time spent on the site (minutes)   |
| `pages_viewed`       | Number of pages viewed during the session |
| `income`             | Annual income of the customer             |
| `age`                | Age of the customer                       |
| `property_type`      | Type of property interested in (categorical) |
| `target_column`      | Binary target variable (1 = success, 0 = failure) |

Sample data is provided in the file `real_estate_data.csv`.

---
