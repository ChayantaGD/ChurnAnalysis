# Customer Churn Analysis Using SQL Server, Power BI, and Python

![1](https://github.com/user-attachments/assets/5ba7cc02-7c1f-47a5-b628-af5b6cc6cb7f)    ![2](https://github.com/user-attachments/assets/21e4229b-0c6d-4721-8ca1-f5e81b5ecdef)


## Project Overview
This project aims to analyze customer churn using a combination of SQL Server for data processing, Power BI for visualization, and Python for machine learning. The project covers the entire data pipeline from extraction and transformation to visualization and predictive modeling.

## Table of Contents
1. Introduction
2. Technologies Used
3. Setup Instructions
4. Usage
5. Recommendations
6. Real-World Applications
7. Contributing


## Introduction
This project addresses a critical business question: "What factors contribute to customer churn, and how can we predict and prevent it?"
      Key components of the project:
- ETL process in SQL Server
- Data Cleaning in SQL Server
- Creating views in SQL for predictions
- Power BI Transformations
- Power BI Visualization & Enhancing Visuals
- Building a Machine Learning Model (Random Forest) in Jupyter Notebook
- Exporting predictions to CSV and visualizing predicted data in Power BI

## Technologies Used
- **SQL Server**: For data extraction, transformation, and loading (ETL).
- **Power BI**: For data visualization and dashboard creation.
- **Python**: For building and training the machine learning model.
- **Jupyter Notebook**: For developing and testing the machine learning model.

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/ChayantaGD/ChurnAnalysis.git
   ```
2. **SQL Server**:
   - Run the scripts on `ChurnPortfolio.ssmssln` to set up the database and clean the data.
3. **Power BI**:
   - Open the `Churn Portfolio.pbix` files in Power BI Desktop to view and interact with the dashboards.
   - Use `bg.svg` as the background image for your dashboard or you can create your own background.
4. **Python**:
   - I have used Jupyter Notebook,you may use any tool as you wish.
     ```
   - Run the `ChurnPrediction.ipynb` notebook to train the model and generate predictions, which are saved to `predictions.csv`.
5. **Data Integration**:
   - Use the `Predictions.csv` file to visualize predicted data in Power BI.
   - The `Customer_Data.csv` file contains the original dataset used for analysis.

## Usage
- Use the SQL scripts to process and clean the data and create views.
- Utilize Power BI for data visualization and insights.
- Run the Python notebook to build and evaluate the machine learning model.
- Integrate the predicted churn data from `predictions.csv` back into Power BI for comprehensive analysis.

## Recommendations
High-risk customer segments: Identify groups with above-average churn rates
Retention strategies: Analyze successful retention cases for insights
Product improvements: Investigate features or services correlated with lower churn
Customer journey mapping: Examine touchpoints that influence churn decisions
By focusing on these areas, teams can develop targeted strategies to reduce churn and improve customer retention.

## Real-World Applications
This project can be highly useful in the real world for businesses looking to understand and reduce customer churn. By identifying patterns and predicting which customers are likely to churn, companies can:
- Develop targeted retention strategies.
- Improve customer satisfaction and loyalty.
- Optimize marketing efforts to retain high-value customers.
- Make data-driven decisions to enhance overall business performance.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
