#AI-Powered E-commerce Sales Dashboard
 Project Overview:
This project is a web-based E-commerce Sales Dashboard developed using Python and Flask. It uses Machine Learning models to predict sales and profit performance while providing interactive visualizations and business insights through Power BI.
The application helps users analyze sales data, forecast future performance, and make data-driven decisions.

#Key Features:
 -Predict future sales using Machine Learning
 -Analyze profit performance with AI models
 -Interactive charts and visual reports
 -Power BI dashboard integration
 -User-friendly web interface built with Flask

#Technologies Used
1)Programming & Frameworks:
 -Python
 -Flask
 -HTML
2)Machine Learning
 -Scikit-learn
 -XGBoost
 -Data Analysis
 -Pandas
 -NumPy
3)Visualization
 -Matplotlib
 -Seaborn
 -Plotly
4)Business Intelligence
 -Microsoft Power BI

# Project Structure
 ai-ecommerce-dashboard/
├── app.py # Main Flask App
├── templates/
│ └── index.html # Web frontend
├── static/ # (Optional) CSS/JS assets
├── model/
│ ├── sales_model.pkl # Trained Sales Regression Model
│ └── profit_model.pkl # Trained Profit Classifier Model
├── Ecommerce.pbix # Power BI Dashboard
├── requirements.txt # Python Dependencies
└── README.md # Project Overview

Installation Steps:
1.Create Virtual Environment
 -python -m venv venv
 -venv\Scripts\activate
2.Install Required Packages
 -pip install -r requirements.txt
3.Configure Power BI Paths
 -Open app.py and update the Power BI Desktop path and dashboard file location according to your system.
Example:
 -POWER_BI_PATH = r"Your Power BI Desktop Path"
 -PBIX_FILE = r"Your Dashboard File Path"
 
 #Machine Learning Models
 1)Sales Prediction
 -Model: Decision Tree Regressor
 -Library: Scikit-learn
 2)Profit Classification
 -Model: XGBoost Classifier
 -Library: XGBoost

#Running the Project
1)Execute the following command:
 python app.py
2)Open your browser and visit:
 http://localhost:5000

#Power BI Dashboard Insights
 -The Power BI dashboard provides:
 -Monthly Sales Analysis
 -Regional Performance Insights
 -Category-wise Profit Analysis
 -Product Sales Comparison
 -Business Performance Tracking

Project Outcome:
 
This project combines Machine Learning, Data Analytics, Web Development, and Business Intelligence into a single application that helps businesses monitor performance, predict future sales, and gain actionable insights from e-commerce data.
