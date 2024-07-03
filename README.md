# End-to-end-machine-learning-project-Telecom-customer-churn

## Project Overview

Predicting customer churn is critical for telecommunication companies to effectively retain customers. Since acquiring new customers is more costly than retaining existing ones, this project aims to develop a predictive model to identify which customers are more likely to churn. By analyzing customer characteristics, we can take proactive measures to reduce churn rates, thereby increasing customer satisfaction and company revenue.

## Objective

The primary objective of this project is to build a data-driven solution that predicts the likelihood of customer churn. The predictive model will analyze three main categories of customer characteristics:
1. Demographic Information
2. Account Information
3. Services Information

## Data Set

The datasets used in this project are sourced from Kaggle and consist of 20 columns representing various characteristics of the customers of a fictional telecommunications corporation. The target variable is the `Churn` column, which indicates whether a customer left the company within the last month (`Yes`) or not (`No`).

### Datasets

There are two datasets used in this project:

1. `churn-bigml-20`: Contains 668 rows (customers) and 20 columns (features).
2. `churn-bigml-80`: Contains 2667 rows (customers) and 20 columns (features).

### Features and Their Meanings

Each row in the dataset represents a customer, and each column contains an attribute or feature of the customer. The dataset includes the following columns:

1. `State`: The state in which the customer resides.
2. `Account length`: The number of months the customer has been with the company.
3. `Area code`: The area code of the customer's phone number.
4. `International plan`: Indicates if the customer has an international calling plan (`yes` or `no`).
5. `Voice mail plan`: Indicates if the customer has a voice mail feature (`yes` or `no`).
6. `Number vmail messages`: The number of voice mail messages the customer has.
7. `Total day minutes`: The total number of minutes the customer used during the day.
8. `Total day calls`: The total number of calls the customer made during the day.
9. `Total day charge`: The total charges incurred by the customer during the day.
10. `Total eve minutes`: The total number of minutes the customer used during the evening.
11. `Total eve calls`: The total number of calls the customer made during the evening.
12. `Total eve charge`: The total charges incurred by the customer during the evening.
13. `Total night minutes`: The total number of minutes the customer used during the night.
14. `Total night calls`: The total number of calls the customer made during the night.
15. `Total night charge`: The total charges incurred by the customer during the night.
16. `Total intl minutes`: The total number of minutes the customer used for international calls.
17. `Total intl calls`: The total number of international calls the customer made.
18. `Total intl charge`: The total charges incurred by the customer for international calls.
19. `Customer service calls`: The number of calls the customer made to customer service.
20. `Churn`: Indicates whether the customer left the company within the last month (`yes` or `no`).

## Analysis

The goal of the analysis is to identify the relationship between customer characteristics and churn. This involves:
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation

## Getting Started

### Prerequisites

To run the project, you will need the following libraries:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Running the Project

1. Prepare the datasets by downloading them from Kaggle and placing them in the `data` directory.
2. Run the Jupyter notebooks or Python scripts provided in the repository to preprocess the data, perform EDA, and build the predictive model.

## Repository Structure

- `data/`: Contains the datasets.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model building.
- `scripts/`: Python scripts for various stages of the project.
- `README.md`: Project overview and instructions.
- `requirements.txt`: List of required Python packages.

## Results

The model evaluation results and performance metrics will be documented in the analysis notebooks and reports.

## Acknowledgments

Special thanks to Kaggle for providing the datasets used in this project.
