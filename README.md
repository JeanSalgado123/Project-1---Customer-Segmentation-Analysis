# Project-1: Customer Segmentation Analysis

## Overview
This project focuses on analyzing customer data to create segments that can help improve marketing strategies and personalization. By effectively segmenting customers, businesses can better tailor their campaigns, offers, and communication strategies to meet the specific needs of different groups.

## Objectives
- Analyze customer data to identify meaningful segments.
- Use clustering algorithms to group customers based on similar characteristics.
- Provide insights to improve marketing personalization and customer engagement.

## Dataset
The dataset contains customer information such as age, gender, income, spending habits, and purchase frequency. It is assumed to be in CSV format and stored in the `data` folder.

## Methodology
1. **Data Collection:** The data is collected from the company's CRM and includes anonymized customer records.
2. **Data Cleaning:** Missing values are handled, and outliers are identified and treated to ensure accurate clustering.
3. **Exploratory Data Analysis (EDA):** Basic statistical analysis and visualizations are used to understand data distribution and relationships.
4. **Clustering Algorithms:** Techniques such as K-Means clustering are applied to group customers based on similarity in attributes.
5. **Evaluation:** The silhouette score and elbow method are used to determine the optimal number of clusters and evaluate the quality of the segmentation.

## Requirements
To run this project, you need the following libraries installed:
```bash
pip install pandas matplotlib scikit-learn joblib
```

## How to Run
1. Clone this repository: `git clone https://github.com/JeanSalgadoAI/Project-1---Customer-Segmentation-Analysis.git`
2. Navigate to the project folder: `cd Project-1---Customer-Segmentation-Analysis`
3. Ensure that the dataset is in the `data` folder.
4. Run the Jupyter Notebook: `jupyter notebook notebooks/Customer_Segmentation.ipynb`

## Results
- The customer segments are visualized using scatter plots and bar charts, highlighting differences in spending patterns and demographics.
- Insights from the segmentation will be provided in the final report, helping the marketing team to develop more effective campaigns.

## Files and Folders
```bash
Project-1---Customer-Segmentation-Analysis
│   README.md
│   LICENSE
│   .gitignore
│
├───data
│    └── raw (contains raw data files)
│
├───models
│    └── model.pkl (contains trained model)
│
├───notebooks
│    └── Customer_Segmentation.ipynb (Jupyter Notebook with analysis)
│
├───reports
│    └── Customer_Segmentation_Report.pdf (final report)
│
└───scripts
     └── generate_project.py (Python script for running analysis)
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

