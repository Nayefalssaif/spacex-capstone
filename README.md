# spacex-capstone
Capstone project for IBM Applied Data Science Professional Certificate – Predicting Falcon 9 first stage landing success.
# SpaceX Falcon 9 Launch Success Prediction 🚀

This project is the final capstone in the **IBM Data Science Professional Certificate**, and it focuses on using data science techniques to analyze and predict the success of SpaceX Falcon 9 first-stage landings.

## 📌 Project Objectives

- Explore and analyze historical launch data.
- Build interactive visualizations and dashboards.
- Develop classification models to predict landing success.
- Gain insights into how variables like **payload mass**, **orbit type**, and **launch site** affect landing outcomes.

## 📂 Project Structure

| Notebook File                                      | Description                                              |
|---------------------------------------------------|----------------------------------------------------------|
| `Data Collection API.ipynb`                       | Extract data from SpaceX REST API                        |
| `jupyter-labs-webscraping.ipynb`                  | Scrape launch data from Wikipedia                        |
| `labs-jupyter-spacex-Data wrangling.ipynb`        | Clean and merge data from both sources                   |
| `EDA with Data Visualization.ipynb`               | Analyze data using charts and visual tools               |
| `EDA with SQL.ipynb`                              | Analyze data using SQL queries via IBM DB2               |
| `Interactive Visual Analytics with Folium.ipynb`  | Visualize launch sites and success via interactive maps  |
| `Machine Learning Prediction.ipynb`               | Build and evaluate classification models (LogReg, Tree…) |

## 📊 Technologies Used

- Python, Pandas, NumPy
- Plotly, Folium, Seaborn
- Scikit-learn (Classification Models)
- SQL (IBM Cloud DB2)
- Dash (Plotly Dash dashboard)

## 🔍 Key Insights

- KSC LC-39A is the most successful launch site.
- Payloads between **2000–5500 kg** show higher success.
- Orbit types **GEO, SSO, ES-L1** have a 100% success rate.
- **Decision Tree** was the best model for classification.

## 🧠 Project Outcome

An interactive dashboard and predictive model to support decision-making and reduce cost by forecasting first-stage landing outcomes.

---

**Developed by:** Naif Alotaibi  
**Course:** IBM Applied Data Science Capstone  
**Platform:** [Coursera](https://www.coursera.org)

