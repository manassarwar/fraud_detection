
README
**Fraud Detection Using Machine Learning and Visualizations**
**Project Overview**
This project focuses on fraud detection using a machine learning pipeline and data visualization tools. It utilizes the PaySim1 dataset from Kaggle to create actionable insights, reports, and visualizations, helping stakeholders identify fraudulent activities. The implementation is divided into three learning objectives (LOs):

**LO1**: Understanding Machine Learning Concepts for Fraud Detection.
**LO2:** Creating Fraud Detection Reports and Visualizations Using Tableau.
**LO3:** Integrating Machine Learning and Visualization for Storytelling and Prescriptive Analytics.
**Dataset**
**Name:** PaySim1 Dataset
**Source: ** Kaggle - PaySim1
**Description:** A synthetic dataset simulating mobile money transactions for fraud detection research.
**Learning Objectives**
**1. Understanding Machine Learning Concepts for Fraud Detection (LO1)**
Implemented machine learning models such as Logistic Regression, Decision Trees, Random Forest, and XGBoost for fraud detection.
Evaluated models using metrics like accuracy, precision, recall, and F1-score.
Visualized model performance using confusion matrices and ROC curves.
**2. Creating Fraud Detection Reports and Visualizations Using Tableau (LO2)**
Prepared data for Tableau dashboards by cleaning and aggregating the dataset.
Exported summary metrics and fraud cases for dashboard creation.
Created interactive dashboards in Tableau to identify fraudulent patterns and key insights.
**3. Integrating Machine Learning and Visualization for Storytelling and Prescriptive Analytics (LO3)**
Combined machine learning predictions with visualizations for comprehensive storytelling.
Used Python visualization libraries (e.g., Seaborn, Matplotlib, Plotly) to complement Tableau dashboards.
Built actionable recommendations for stakeholders using data-driven storytelling.
**Folder Structure**

.
├── data/
│   ├── PS_20174392719_1491204439457_log.csv    # Original dataset
│   ├── prepared_fraud_data.csv                # Cleaned and aggregated data
│   ├── fraud_summary_metrics.csv              # Summary metrics for Tableau
│   ├── fraud_case_study.csv                   # Case study data for Tableau
├── notebooks/
│   ├── Fraud_Detection.ipynb           # Machine learning implementation
              # Integrated ML and visualization
├── results/
│   ├── model_performance.png                  # Model performance metrics
│   ├── transaction_type_distribution.png      # Fraud distribution by transaction type
│   ├── fraud_trends_by_day.png                # Fraud trends over time
├── README.md                                  # Project documentation
Prerequisites
To run the code in this project, ensure you have the following installed:

Python 3.7 or higher
Jupyter Notebook
Required Python libraries:
pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
plotly
Tableau Desktop (for LO2 visualizations)
Setup and Usage
**1. Clone the Repository**

git clone https://github.com/your-repo/fraud-detection-visualization.git
cd fraud-detection-visualization
**2. Install Dependencies**

pip install -r requirements.txt
**3. Download Dataset**
Download the PaySim1 dataset from Kaggle:

Link: Kaggle - PaySim1
Place the dataset in the data/ folder.
**4. Run Notebooks**
Open Jupyter Notebook and run the notebooks in the following order:

Fraud_Detection.ipynb (Machine learning models for fraud detection)

**5. Visualize in Tableau**
Import the exported files (prepared_fraud_data.csv, fraud_summary_metrics.csv, fraud_case_study.csv) into Tableau.
Follow the steps in the notebooks to create fraud detection dashboards.
**Results and Key Insights**
Machine learning models achieved high accuracy and precision in detecting fraud.
Tableau dashboards provided clear insights into fraud patterns, transaction types, and trends.
Interactive visualizations enable stakeholders to make data-driven decisions.
**References**
Kaggle. (n.d.). PaySim1 Dataset. Retrieved from https://www.kaggle.com/datasets/ealaxi/paysim1
Other references are cited in the project notebooks.
