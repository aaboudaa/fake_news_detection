# fake_news_detection

## Description:
This machine learning project focuses on building a machine learning model to detect fraudulent job postings. This project utilizes a dataset containing information about various job postings, including job titles, locations, descriptions, and other features.

You can find the .CSV file in the link below :
👇👇👇👇

<https://drive.google.com/file/d/16j-Z0zSDPQY78QEuP7Ncnpea5r6MXAp7/view>

## Key Steps and Insights:

**1. Data Preprocessing:** TThe project begins with loading and preprocessing the dataset. Missing values in the 'department' column are filled with the mode value, and categorical and numerical features are identified.

**2. Data Transformation:** The project uses techniques like one-hot encoding and simple imputation to transform the data into a suitable format for machine learning. Categorical features are one-hot encoded, and missing values are imputed.

**3. Model Building:** A Random Forest Classifier is chosen as the classification model for detecting fake job postings. The model is trained on the transformed data.

**4. Model Evaluation:** The project evaluates the model's performance using accuracy as a metric. Additionally, a classification report is generated, providing insights into precision, recall, and F1-score.
