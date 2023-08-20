# Customer Churn Prediction: Vodafone Corporation

![Customer_Churn](Images/churn.jpg) 

*Predicting customer churn using machine learning to ensure customer satisfaction and better retention rates.*

## Quick Links
| Platform | Link |
|----------|------|
| LinkedIn Article | [View Article](https://www.linkedin.com/pulse/customer-churn-analysis-telecom-industry-faith-mwai) |
| GitHub Code | [Access Code](https://github.com/Faith-theAnalyst/Telco_Customer_Churn_Analysis) |
| PowerBI Dashboard* | [See Dashboard](https://app.powerbi.com/groups/me/reports/660a3949-00ac-488d-b245-09382d42ac7e/ReportSectionabea9013b0e4c1eadcdc?experience=power-bi) |

**Disclaimer:** Viewing the Python script dashboard on PowerBI requires a PowerBI Pro license.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Results and Insights](#results-and-insights)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [Setup and Run](#setup-and-run)
- [Contributors](#contributors)
- [License](#license)

## Introduction
Customer churn, also known as customer attrition, in the telecom sector is one of the primary metrics companies try to minimize. A higher churn rate indicates a larger number of customers leaving the service, which results in revenue loss. This project focuses on predicting customer churn to provide insights that can help Vodafone Corporation take proactive measures.

## Data
The dataset contains monthly behavior data of Vodafone customers, along with demographic details and their churn status.

**Features include**:
- Demographic details like gender, senior citizen status.
- Services used such as phone service, internet service.
- Monthly charges, total charges, and tenure.
- Customer feedback metrics like online security, tech support, and streaming services.

Data Source: This data was provided by Vodafone Corporation's sales and marketing team.

## Methodology
- **Data Cleaning and Pre-processing**: Handled missing values, outlier treatment.
- **Exploratory Data Analysis**: Analyzed patterns, distributions, correlations, and churn rate.
- **Feature Engineering**: Generated new features from existing data to provide more insights.
- **Model Development**: Implemented models like Random Forest, XGBoost, and Gradient Boosting to predict churn.
- **Evaluation**: Used metrics such as accuracy, precision, recall, and F1-score to evaluate the model's performance.

## Technologies Used
- **Language**: Python
- **Libraries**: Pandas, Numpy, Scikit-learn, XGBoost, Seaborn, Matplotlib
- **Environment**: Jupyter Notebook

## Results and Insights
- Random Forest and XGBoost gave the best performance with an accuracy of around 86%.
- Important features influencing churn included monthly charges, contract type, and online security.
- Customers with month-to-month contracts and no online security feature showed a higher likelihood of churning.

## Project Structure
- `Data/`: Directory containing all data files
- `Notebook/`: Jupyter notebooks for exploratory analysis and modeling
- `PowerBi/`: Python scripts for PowerBi Deployment
- `Results/`: Directory storing model results and outputs

## Future Improvements
- Test deep learning models for better accuracy.
- Incorporate feedback from on-ground sales teams for feature engineering.
- Explore ensemble techniques to combine model predictions.

## Setup and Run
1. Clone the repository: `git clone <https://github.com/Faith-theAnalyst/Telco_Customer_Churn_Analysis>`
2. Install necessary packages: `pip install -r requirements.txt`
3. Open Jupyter notebook and run the main notebook: `customer_churn_analysis.ipynb`

## Contributors
- [Faith Mwai](https://www.linkedin.com/in/faith-esther-njugu-mwai/)

## License
This project is licensed under the MIT License. 

---

