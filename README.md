# Customer Churn Prediction

This project focuses on predicting customer churn using machine learning. The dataset contains customer details and various features that may influence whether a customer will churn or not. We employ a **Random Forest Classifier** to build a model for churn prediction and generate actionable business insights.

---

## Features

- **Data Collection & Preprocessing:** Data is loaded, missing values are handled, and features are scaled for better model performance.
- **Model Building:** A Random Forest Classifier is used for predicting churn, offering high accuracy and feature importance.
- **Insights Generation:** After training the model, we extract key features and provide actionable business recommendations.
- **Data Visualization:** Visualizes correlations and relationships in data through heatmaps and pair plots.

---

## Steps in the Process


### 1. **Data Loading and Exploration**
- Loads customer data from a CSV file.
- Performs basic exploration including dataset shape, null value count, and statistical summaries.
- Ensures a deeper understanding of the data distribution and structure.

---
### 2. **Data Visualization**
- Generates a heatmap to show correlations between features.
- Creates pairplots categorized by churn status to explore feature relationships and patterns.
- Helps in identifying key trends and interactions in the data.

---

### 3. **Data Preprocessing**
- Handles missing values by imputing with the mean for `avg_order_value`.
- Engineers new features, such as `days_as_customer`, for enhanced prediction accuracy.
- Scales numerical features for better model performance using StandardScaler.

---

### 4. **Data Splitting**
- Splits the dataset into training and testing sets to evaluate model performance.
- Ensures that 30% of the data is reserved for testing while maintaining reproducibility.

---

### 5. **Model Building and Evaluation**
- Employs a Random Forest Classifier for its robustness and feature importance insights.
- Evaluates the model using a classification report, confusion matrix, and cross-validation scores.
- Provides a comprehensive view of the model’s performance and reliability.

---

### 6. **Generating Insights**
- Extracts feature importance from the trained model to identify the top contributing factors to churn.
- Offers actionable recommendations based on the most significant features:
  - Reach out to less active customers with personalized offers.
  - Address recurring support issues by improving workflows.
  - Provide incentives to new customers to extend their engagement.

---

## Key Highlights
- **Actionable Insights:** The project not only predicts churn but also provides strategies to reduce it.
- **Scalable Model:** The Random Forest Classifier can handle complex relationships and large datasets effectively.
- **Data-Driven Approach:** The analysis leverages visualization and statistical summaries to guide decision-making.

---

## Next Steps
- Implement the model in real-world scenarios to evaluate its business impact.
- Expand the dataset to include more features and improve prediction accuracy.
- Explore advanced techniques like hyperparameter tuning or alternative algorithms for further optimization.





