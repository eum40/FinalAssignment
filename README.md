# Federal-State Level Predicting Veteran Suicide Rates (2005–2011)

Purpose: This project uses machine learning models to analyze and predict veteran suicide rates across U.S. states from 2005 to 2011.

Models Used: Linear Regression; Lasso Regression; Random Forest Regression; Optimized Random Forest Regression

Key Findings: Among four models run, the optimized Random Forest model achieved the best performance with an R² score of 0.951 and an MSE of 6.01, significantly outperforming both Linear Regression (R² = 0.75) and Lasso Regression (R² = 0.72). This result suggests that the relationship between the predictors and veteran suicide rates is likely nonlinear and complex—well-captured by the ensemble learning method. Results suggested that some demographic data had some impact on predictive models; however, macro-level factors such those variables with broader state context, are the most powerful predictors of veteran suicide rates in this dataset.

Files: Full analysis notebook; Short video walkthrough; Output visualizations

Dataset: [Kaggle: US Veteran Suicides](https://www.kaggle.com/datasets/residentmario/us-veteran-suicides)

Important Disclaimer: This work was developed as part of an academic course assignment and is intended solely for educational and demonstration purposes. The analysis, predictions, and interpretations presented here are based on publicly available data and may contain inaccuracies, simplifications, and errors. The results do not represent clinical, policy, or governmental recommendations. The dataset used in this project—“US Veteran Suicides” (2005–2011)—was obtained from Kaggle, which in turn sourced the data from News21, an investigative journalism initiative. The original source of the data is: News21 (2013). “Back Home: The Challenges Facing Post-9/11 Veterans.” Retrieved from https://backhome.news21.com/. I used data to practice course assignment requirements like data formatting and data cleaning for machine learning purposes. The author of this project does not claim responsibility for any decisions made based on the findings herein.

Author: Emre Umucu
