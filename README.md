Mall Customer Segmentation using K-means Clustering
Project Overview
This project aims to segment mall customers based on their purchasing behavior using the K-means clustering algorithm. By analyzing customer data, we identify distinct groups of customers, which can help in developing targeted marketing strategies and improving customer experience.
Dataset
The dataset contains information about mall customers, including:
Customer ID
Gender
Age
Annual Income (k$)
Spending Score (1-100)
Methodology
Data Exploration: Analyzed the distribution and relationships between different features.
Data Visualization: Created various plots to understand the data better.
3. Feature Selection: Used Principal Component Analysis (PCA) to identify high-variance features.
Clustering: Applied K-means algorithm to segment customers.
Results Visualization: Plotted the resulting clusters for easy interpretation.
Key Findings
Identified 5 distinct customer segments:
High income, high spenders
Low income, low spenders
3. Average income and spending
High income, low spenders
Low income, high spenders
Tools and Libraries Used
Python 3
Pandas for data manipulation
NumPy for numerical operations
Scikit-learn for machine learning algorithms
Matplotlib and Seaborn for data visualization
How to Run
Clone this repository
Install required libraries: pip install -r requirements.txt
Run the Jupyter notebook: jupyter notebook Mall_Customer_Segmentation.ipynb
Future Work
Implement more advanced clustering algorithms
Incorporate more customer data for better segmentation
Develop a dashboard for real-time customer segmentation
Contributors
[Your Name]
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
