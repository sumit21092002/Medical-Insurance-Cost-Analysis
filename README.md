# Medical Insurance Cost Analysis & Predictive Modeling

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.x-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Latest-blue)

## Project Overview
Comprehensive analysis of a medical insurance dataset (100,000 records) to understand cost drivers, build predictive models, and provide actionable business insights.

**Key Objectives:**
- Identify factors driving medical costs
- Build high-accuracy regression and classification models
- Segment customers using clustering
- Provide profitability and risk management recommendations

## Key Findings
- Smoking status, age, and chronic conditions are the strongest predictors of cost
- Gradient Boosting model achieved **R² ≈ 0.99** on cost prediction
- High-risk seniors (Cluster 2) drive disproportionate costs
- Platinum tier shows tight margins → pricing adjustment recommended

## Technologies Used
- **Python** with pandas, numpy, matplotlib, seaborn
- **Machine Learning**: Random Forest, HistGradientBoosting, K-Means clustering
- **Statistical Analysis**: ANOVA, Tukey HSD, feature importance

## Notebook Structure
- Data inspection and cleaning
- Exploratory data analysis with visualizations
- Feature engineering
- Predictive modeling (regression & classification)
- Customer segmentation
- Profitability analysis
- Business recommendations

## Results
- Cost Prediction Model: R² ~0.99
- High-Risk Classification: Accuracy 97.8%
- 4 distinct customer clusters identified

## How to Run
1. Clone this repo
2. Install requirements: `pip install pandas numpy matplotlib seaborn scikit-learn statsmodels`
3. Open and run `medical_insurance_analysis.ipynb` in Jupyter

## Future Improvements
- Deploy model as web app (Streamlit/Flask)
- Incorporate real-time data
- Add cost-benefit analysis of interventions

---
*Portfolio project by Sumit Sarode • Data Analyst • January 2026*
