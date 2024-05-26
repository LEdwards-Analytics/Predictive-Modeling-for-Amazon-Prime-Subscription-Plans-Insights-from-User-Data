# Predictive Modeling for Amazon Prime Subscription Plans: Insights from User Data

## Overview
This repository contains code and documentation for a predictive modeling project focused on predicting subscription plans for Amazon Prime users. The project utilizes machine learning techniques to analyze user data and predict whether users will subscribe to annual or monthly subscription plans.

## Project Structure
- `notebooks/`: Contains Jupyter Notebooks for data preprocessing, exploratory data analysis (EDA), model development, and evaluation.
- `data/`: Directory for storing the dataset used in the project.
- `docs/`: Documentation files, including the project summary.
- `README.md`: Project overview, including instructions for running the code and interpreting the results.

<<<<<<< HEAD
## Key Deliverables
- **Code Notebook**: A comprehensive Jupyter Notebook containing data preprocessing, EDA, model development, and evaluation.
- **Project Summary**: A concise one-page summary highlighting key findings, model performance, and actionable insights.
=======
The main purpose of analyzing Amazon Prime Subscriber data is to:
1. Understand the demographic and behavioral patterns of Amazon Prime subscribers.
2. Explore the data to determine what features to use in the model.
3. Create a model to provide valuable insights into user behavior and preferences, enabling data-driven decision-making for subscription-based businesses.

## Data Source 📊

The data is from: 
https://www.kaggle.com/datasets/arnavsmayan/amazon-prime-userbase-dataset 

It includes the following columns:

| **Field**                       | **Description**                                                      |
|---------------------------------|----------------------------------------------------------------------|
| **User ID**                     | Numeric ID for the user                                              |
| **Name**                        | User's name                                                          |
| **Email Address**               | User's email address                                                 |
| **Username**                    | Username                                                             |
| **Date of Birth**               | Date of Birth of the user                                            |
| **Gender**                      | User's gender                                                        |
| **Location**                    | User's Country                                                       |
| **Membership Start Date**       | Start date of the Amazon Prime membership                            |
| **Membership End Date**         | End date of the membership                                           |
| **Payment Information**         | Payment method used (Visa, Mastercard, Amex)                         |
| **Renewal Status**              | Setting of renewal on subscription (Manual vs Automatic)             |
| **Usage Frequency**             | Frequency of platform usage (Occasional, Regular, Frequent)          |
| **Purchase History**            | Most frequently purchased items                                      |
| **Favorite Genres**             | Favorite genre of content                                            |
| **Devices Used**                | Device used to access the platform                                   |
| **Engagement Metrics**          | Engagement level (Low, Medium, High)                                 |
| **Feedback/Ratings**            | Average feedback/ratings given by the user                           |
| **Customer Support Interactions**| Number of interactions with customer support                        |
| **Subscription Plan**           | Type of subscription plan (Annual vs Monthly)                        |

>>>>>>> 25e0947a9aef3e8ad203f0b36f879855b173b6ad

## Getting Started
1. Clone the repository to your local machine.
2. Navigate to the `notebooks/` directory and open the Jupyter Notebook.
3. Follow the instructions in the notebook to execute the code and analyze the data.
4. Refer to the project summary for key insights and recommendations.

## Dependencies
The project utilizes the following Python libraries:
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost

Ensure these dependencies are installed before running the code.

## License
This project is licensed under the MIT License.

## Project Summary
[Link to Project Summary Document

## Recommendations
Based on the analysis and modeling conducted, here are some recommendations for optimizing subscription plans and user retention:

* Personalized Subscription Plans: Utilize the insights from the predictive models to offer personalized subscription plans tailored to individual user preferences, usage frequency, and engagement metrics. This can enhance user satisfaction and retention by providing plans that better suit their needs.

* Promotional Campaigns: Target promotional campaigns towards users who are more likely to churn based on the predictive models. Offer incentives or discounts to encourage them to renew their subscriptions or upgrade to higher-tier plans.

* Content Recommendations: Leverage the favorite genres and purchase history of users to provide targeted content recommendations. This can increase user engagement and satisfaction by delivering content that aligns with their interests.

* Customer Support Enhancement: Identify users who have had frequent interactions with customer support and proactively address their concerns or issues. Improving the customer support experience can lead to higher retention rates and positive feedback.

* Optimized Renewal Strategies: Implement strategies to optimize subscription renewal processes, such as providing seamless renewal options, offering incentives for automatic renewal, or sending timely reminders before subscription expiration dates.

* Continuous Monitoring and Feedback: Regularly monitor user feedback and engagement metrics to identify evolving preferences and trends. Incorporate user feedback into product development and subscription offerings to ensure continued relevance and satisfaction.

* Further Model Refinement: Continuously refine and update the predictive models based on new data and feedback. This can improve the accuracy and effectiveness of the models over time, leading to better decision-making and outcomes.\

* More data: This model could be significantly improved with more datapoints.