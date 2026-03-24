# Data-Science-Capstone-Project-Report

## SpaceX Falcon 9 First Stage Landing Prediction

This project is the final capstone for the IBM Data Science Professional Certificate. The primary objective is to predict whether the first stage of the Falcon 9 rocket will land successfully, which is a key factor in reducing launch costs from $165 million to approximately $62 million.

🚀 Project Overview
By accurately predicting landing success, we can estimate the actual cost of a launch and provide valuable insights for commercial space race competition. This project follows a complete Data Science pipeline:
Data Collection: Gathering telemetry from the SpaceX REST API and historical records via Wikipedia web scraping.
Data Wrangling: Cleaning, filtering for Falcon 9, and performing feature engineering.
Exploratory Data Analysis (EDA): Using SQL for database queries and Matplotlib/Seaborn for visual patterns.
Interactive Analytics: Mapping launch sites with Folium and building a real-time dashboard with Plotly Dash.
Machine Learning: Training and optimizing classification models (Logistic Regression, SVM, Decision Tree, KNN).

📊 Key Results
Predictive Accuracy: All classification models achieved a consistent 83.33% accuracy on the test set.
Optimal Performance: KSC LC-39A was identified as the most successful launch site with a 76.9% success rate.
Payload Insight: A "sweet spot" for successful landings was discovered for payloads between 2,000 kg and 6,000 kg.
Technological Maturity: Newer booster versions show significantly higher reliability compared to earlier iterations.

🛠️ Tools and Technologies
Languages: Python Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly Dash, BeautifulSoup 
Database: SQL (SQLite/IBM Db2) 
Environment: Jupyter Notebooks

📂 Project Structure
notebooks/: Contains the Jupyter notebooks for each phase (Data Collection, EDA, Folium, ML).
scripts/: Contains the spacex-dash-app.py script for the Plotly Dash dashboard.
presentation/: Includes the final project report in PDF 
format.data/: Contains the processed datasets used in the analysis.

🔗 How to Use
Clone the repository.
Install the required libraries: pip install pandas dash folium scikit-learn.
Run the dashboard: python scripts/spacex-dash-app.py.
Explore the notebooks to see the step-by-step analysis.
