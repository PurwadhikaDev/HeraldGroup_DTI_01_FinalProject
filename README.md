# Bank Telemarketing Campaign
**By Herald Team**
- Edwardo Krisna Sembiring
- Friska Hermalia Putri
- Muhammad Alditya Prasetyawan
## Project Overview

The **Bank Telemarketing Campaign** project aims to develop a data-driven approach to enhance the effectiveness of telemarketing efforts for term deposit subscriptions. By leveraging advanced analytics and machine learning techniques, we seek to identify potential customers who are more likely to subscribe to a term deposit, thereby improving success rate.

## Context
A Portuguese bank is conducting telemarketing campaigns to encourage customers to make term deposits. The bank wants to improve its campaign efficiency and increase deposit conversion rates, especially given the importance of deposits for bank stability highlighted by the 2008 financial crisis. The bank has data from previous campaigns, including customer demographics, contact details, campaign outcomes, and relevant economic indicators. They want to use this data to predict which customers are more likely to agree to a term deposit, allowing them to target their efforts more effectively and reduce wasted resources.

## Objectives
- Develop a predictive model to forecast the probability of customers opening a term deposit, enabling the financial team to optimize budget allocation and reduce unnecessary expenses in telemarketing campaigns.
- Identify key factors influencing customer decisions to open term deposits, providing the marketing team with actionable insights for targeted customer engagement and improved conversion rates.

## Project Structure

### 1. Problem Statement
- Define the challenge of low conversion rates in telemarketing campaigns
- Set objectives for improving campaign effectiveness

### 2. Data Understanding
- Load dataset (41,188 rows, 21 columns)
- Inspect data types and distributions

### 3. Exploratory Data Analysis
- Compute descriptive statistics
- Visualize key relationships and patterns
- Generate insights from customer and campaign characteristics to deposit

### 4. Data Cleaning and Preprocessing
- Identify missing values and outliers
- Handle missing values (create original and imputed datasets)
- Remove irrelevant features
- Address class imbalance
- Perform feature encoding and scaling

### 5. Methodology (Modeling)
- Benchmark multiple ML models
- Conduct feature selection
- Perform hyperparameter tuning
- Evaluate model performance using precision and other metrics

### 6. Conclusion and Recommendation
- Summarize key findings
- Propose strategies to increase conversion rates
- Suggest areas for future improvement

## Run

1. Clone or download this repo first.
2. Install the dependencies package/library by running on the terminal `pip install -r requirements.txt` or other way (like conda).

## Contributing

Contributions to this project are welcome. If you have any ideas or improvements, feel free to fork the repository and submit a pull request. Please make sure your changes are well-documented and aligned with the project objectives.

## Acknowledgments

- **Purwadhika Digital Technology School**: For providing the learning platform and guidance throughout the project.
- **Lecturer**: Mohammad Digjaya for his valuable input and support.
- **Data Sources**: The dataset used in this project is from the UCI Machine Learning Repository. [Go to Dataset](https://www.kaggle.com/datasets/volodymyrgavrysh/bank-marketing-campaigns-dataset)

Visit our tableau to see the model predictive performance and analysis! [Go to Tableau](https://public.tableau.com/views/HeraldBankMarketingCampaign/Dashboard5?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
