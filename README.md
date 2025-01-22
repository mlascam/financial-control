# Financial Control Project

## Motivation
This project was born out of a desire to help a friend struggling with financial management. By addressing the imbalance between their income and expenses, the goal is to foster better spending habits, enable savings, and optimize the use of their money.

## Project Goals
1. **Data Collection**: Accumulate and process credit card statements to create a structured dataset.
2. **Data Exploration**: Develop an interactive dashboard in Tableau to analyze and visualize spending trends.
3. **Machine Learning Implementation**: Design an algorithm to predict future financial behavior based on historical data, providing actionable insights for improved financial planning.

## Key Features
- **PDF Processing**: Extract transaction data from credit card statements in PDF format (Visa, Amex, MasterCard).
- **Data Homogenization**: Standardize the format of dates and amounts to create a cohesive dataset.
- **Predictive Analytics**: Implement a machine learning model to forecast spending and identify potential areas for cost optimization.

## Tools and Technologies
- **Python**: Used for data extraction and preprocessing.
- **Tableau**: Chosen for building the dashboard to explore and analyze the data.
- **Machine Learning**: Future implementation to create predictive models.

## Folder Structure
```
Financial-Control/
├── raw_pdfs/          # PDFs containing credit card statements
├── processed_data/    # Extracted and standardized CSV files
├── notebooks/         # Jupyter Notebooks for data preprocessing and analysis
├── scripts/           # Python scripts for PDF processing
└── README.md          # Project documentation
```

## How to Use
1. **Set up the environment**:
   - Install the required libraries:
     ```bash
     pip install -r requirements.txt
     ```
2. **Process PDFs**:
   - Use the provided scripts to extract and standardize transaction data.
3. **Visualize Data**:
   - Import the processed CSV files into Tableau to explore spending trends.
4. **Run Machine Learning Models**:
   - Once implemented, use the notebooks to predict future financial behavior.

## Future Work
- **Algorithm Optimization**: Refine the machine learning model for improved prediction accuracy.
- **Integration**: Develop an automated pipeline to update the dashboard with new data.
- **Behavioral Insights**: Leverage clustering techniques to categorize spending patterns.

## Acknowledgments
This project is dedicated to helping others achieve financial stability and improve their quality of life through data-driven insights.
