# SpaceX Falcon 9 Landing Prediction: An End-to-End Data Science Analysis

## 🚀 Executive Summary
The main objective of this project is to predict the successful landing of the Falcon 9 first stage to estimate launch costs for Space Y, a competitor to SpaceX. By analyzing historical launch data, we determined that the first stage recovery significantly reduces the cost of a launch. Our predictive models achieved an accuracy of **83.33%**, providing a reliable tool for cost estimation and bidding strategies.

## 📂 Project Structure
The project follows a linear workflow, organized as follows:

- **1_Data_Collection_API.ipynb**: Collecting data from the SpaceX REST API.
- **2_Data_Collection_WebScraping.ipynb**: Scraping historical launch data from Wikipedia.
- **3_Data_Wrangling.ipynb**: Cleaning data, handling missing values, and One-Hot Encoding.
- **4_EDA_SQL.ipynb**: Exploratory Data Analysis using SQL queries.
- **5_EDA_Visualization.ipynb**: Visualizing trends and relationships using Matplotlib/Seaborn.
- **6_Interactive_Maps_Folium.ipynb**: Geospatial analysis of launch sites using Folium.
- **7_Machine_Learning.ipynb**: Building and evaluating predictive models (LogReg, SVM, Tree, KNN).
- **spacex_dash_app.py**: Plotly Dash application for interactive payload analysis.

## 🌟 Highlights & Innovation
Beyond the standard requirements, this project includes:
- **Deep Data Insights:** Analysis of the high-success cluster in the 2k-4k payload range.
- **Visual Creativity:** Integration of thematic rocket imagery and custom flowcharts.
- **Professional Polish:** Copyright watermarks on slides and a technical Appendix for model transparency.

## 📊 Key Findings
1.  **Launch Success:** Success rates have improved significantly over time, particularly with the transition to FT boosters.
2.  **Payload Analysis:** There is a distinct high-success cluster in the **2,000kg–4,000kg** payload range.
3.  **Launch Sites:** KSC LC-39A has become a primary site for successful missions.
4.  **Model Performance:** Logistic Regression, SVM, and KNN all tied for the best performance with **83.33%** accuracy on the test set.

## 🛠️ Tools & Technologies
- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Folium, Plotly Dash
- **API:** SpaceX REST API

## 📝 Author
IBM Data Science Professional Certificate Capstone Project.
