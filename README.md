# Optimal Cricket Team Prediction Using ML & DL

## Overview
This project focuses on predicting an optimal cricket team composition using a combination of Machine Learning (ML) and Deep Learning (DL) techniques. The goal is to analyze historical player performance data and identify the best players based on metrics like runs, strike rate, wickets, and economy rates.

## Objectives
- **Data Analysis**: Preprocess and analyze player statistics (batting, bowling, and all-rounder performance).
- **ML & DL Models**: Develop and compare ML and DL models for player selection.
- **Visualization**: Present results using Tableau for actionable insights.

---

## Dataset
- Data was sourced from historical cricket statistics, including batting, bowling, and all-rounder performance metrics.
- Preprocessing steps included missing value imputation, feature standardization, and dataset aggregation.

---

## Models Implemented
1. **Machine Learning Models**:
   - Logistic Regression
   - Random Forest (Best Performing Model)
   - SVM
   - Decision Tree

2. **Deep Learning Model**:
   - Artificial Neural Network (ANN)

## Results
- **Best Model**: Random Forest with 95.5% accuracy and high F1-Score, making it the most reliable model for predicting optimal players.
- ANN demonstrated potential but required more data for further optimization.

## Visualizations
- **Tableau Dashboards**:
  - Combined contribution bar charts.
  - Player performance comparisons.
  - Team composition metrics.

---

## Key Findings
- Random Forest achieved the best balance between precision, recall, and F1-Score.
- Tableau visualizations provided actionable insights into player contributions.
- Data preprocessing was critical in ensuring accurate and interpretable results.

---

## Future Work
1. Incorporate additional player metrics such as fielding and match conditions.
2. Experiment with advanced ensemble techniques (e.g., stacking).
3. Extend analysis to other cricket formats like Test and T20.

---

## How to Run the Code
- This project was developed using Python, Tableau, and Jupyter Notebooks. So ensure you have colab or Anaconda installed on your system.
- Clone the repository
  ```
    git clone https://github.com/AmmarAhmedl200961/Optimal-Cricket-Team-Prediction-Using-ML-DL.git
  ```
- Explore the notebooks by opening them in Jupyter Notebook or Google Colab.
- Run the code cells to reproduce the results.
- Explore the Tableau dashboards:
   - Download Tableau Public and open the `.twbx` file included in the repository.

---

## Acknowledgments
Special thanks to all contributors and resources that helped bring this project to fruition. The Tableau dashboards and predictive models are the result of collaborative efforts and practical application of data science techniques.

---

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.