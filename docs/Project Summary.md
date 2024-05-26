# Project Summary

## Overview

The goal of this project was to analyze Amazon subscriber data to build predictive models that identify factors influencing subscription plan choices (Annual vs. Monthly). By understanding these factors, Amazon can enhance its offerings and marketing strategies to improve customer retention and satisfaction.

## Data Overview

The dataset includes various features related to Amazon subscribers, such as user demographics, usage patterns, and engagement metrics. Below is a summary of the key features:

| **Field**                        | **Description**                                                     |
|----------------------------------|---------------------------------------------------------------------|
| **User ID**                      | Numeric ID for the user                                             |
| **Name**                         | User's name                                                         |
| **Email Address**                | User's email address                                                |
| **Username**                     | Username                                                            |
| **Date of Birth**                | Date of Birth of the user                                           |
| **Gender**                       | User's gender                                                       |
| **Location**                     | User's Country                                                      |
| **Membership Start Date**        | Start date of the Amazon Prime membership                           |
| **Membership End Date**          | End date of the membership                                          |
| **Payment Information**          | Payment method used (Visa, Mastercard, Amex)                        |
| **Renewal Status**               | Setting of renewal on subscription (Manual vs Automatic)            |
| **Usage Frequency**              | Frequency of platform usage (Occasional, Regular, Frequent)         |
| **Purchase History**             | Most frequently purchased items                                     |
| **Favorite Genres**              | Favorite genre of content                                           |
| **Devices Used**                 | Device used to access the platform                                  |
| **Engagement Metrics**           | Engagement level (Low, Medium, High)                                |
| **Feedback/Ratings**             | Average feedback/ratings given by the user                          |
| **Customer Support Interactions**| Number of interactions with customer support                        |
| **Subscription Plan**            | Type of subscription plan (Annual vs Monthly)                       |

## Methodology

### Data Preprocessing

1. **Handling Missing Values**: Rows with missing values were removed to ensure data integrity.
2. **Feature Encoding**: Categorical variables were encoded using one-hot encoding and others encoded ordinally.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution and relationships within the data. Key insights include:
- Distribution of gender, favorite genres, and usage frequency.
- Correlation analysis to identify relationships between features.

### Model Development

Three machine learning models were developed and evaluated:

1. **Decision Tree Classifier**
2. **Random Forest Classifier** (Non-Tuned and Tuned)
3. **XGBoost Classifier**

### Model Evaluation

Models were evaluated using F1 score, recall, precision, and accuracy metrics. The results are as follows:

| **Model**              | **F1**    | **Recall** | **Precision** | **Accuracy** |
|------------------------|-----------|------------|---------------|--------------|
| Decision Tree          | 0.546140  | 0.582330   | 0.514180      | 0.518000     |
| Random Forest (Non-Tuned) | 0.536650  | 0.521630   | 0.552560      | 0.528000     |
| Random Forest (Tuned)    | 0.547655  | 0.555215   | 0.540299      | 0.521600     |
| XGBoost                | 0.483871  | 0.501672   | 0.505600      | 0.492611     |

### Cross-Validation

Cross-validation was performed to ensure model robustness. The cross-validation accuracy was approximately 51.36% with a standard deviation of ±2.14%.

## Key Findings

1. **Model Selection**: The Decision Tree Classifier was selected as the final model due to its higher accuracy, recall, and precision, making it the most balanced and interpretable model.
2. **Feature Importance**: Important features identified included usage frequency, engagement metrics, and renewal status.
3. **Recommendations**: Focus on improving engagement and providing incentives for manual renewal users to switch to automatic renewal to increase annual subscriptions.

## Conclusion

The predictive model provides valuable insights into the factors influencing subscription plan choices. Although the accuracy could be improved with a larger dataset, the current model offers actionable insights for enhancing customer retention strategies.

## Future Work

- **Data Enrichment**: Collect more data to improve model accuracy and generalization.
- **Feature Engineering**: Explore additional features and interactions to enhance model performance.
- **Advanced Models**: Experiment with advanced machine learning techniques and ensemble methods.

## Contact

For questions or further information, please contact [Your Name] at [Your Email Address].

## License

This project is licensed under the MIT License.
