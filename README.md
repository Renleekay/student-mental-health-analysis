# Student Behavior and Mental Health Analysis

## Project Overview

This project explores the relationship between academic habits, lifestyle behaviors, and mental health outcomes among college students. Using a simulated dataset of one million student records, exploratory data analysis and machine learning techniques were applied to find patterns and build a predictive model for depression scores. This project was completed as a learning exercise to practice exploratory data analysis and machine learning workflows using large-scale datasets.

The analysis investigates how factors such as study habits, screen time, lifestyle behaviors, and financial stress relate to both academic performance and psychological well-being.

---

## Dataset

The dataset contains **1,000,000 student records and 42 variables** representing:

- Academic performance metrics (GPA, final scores, assignment completion)
- Study habits and behavioral indicators
- Lifestyle variables (screen time, gaming hours, late-night activity)
- Social and environmental factors
- Psychological indicators (stress, anxiety, depression)

The dataset used in this project is **synthetic**, meaning it was generated for analysis and learning purposes rather than collected from real individuals.

---

## Methods

The project follows a typical data science workflow:

1. Data loading and inspection
2. Data structure and missing value analysis
3. Exploratory data analysis (EDA)
4. Correlation analysis and visualization
5. Predictive modeling using Linear Regression
6. Model evaluation using R² score and residual analysis

Key tools used:

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

Install dependencies using:

```
pip install -r requirements.txt
```

---

## Key Findings

Several important patterns emerged from the analysis:

- Academic behaviors such as **study hours, assignment completion, and concentration** show strong correlations with **GPA and final scores**.
- Lifestyle variables including **screen time, gaming hours, and late-night activity** tend to cluster together.
- **Financial stress, anxiety, and stress levels** show measurable relationships with depression scores.
- A linear regression model achieved extremely high predictive accuracy **(R² ≈ 0.9999).** Because the dataset is synthetic, relationships between variables are cleaner than those typically observed in real-world data.

Residual analysis confirmed that prediction errors were generally small and centered around zero, indicating strong model performance.

---

## Visualizations

The analysis includes several visualizations to understand the dataset:

- Correlation heatmap of behavioral and academic variables
- Scatter plots exploring relationships between key features
- Predicted vs. actual values for model evaluation
- Residual analysis for regression performance

---
## How to Run

1. Clone this repository
2. Install required libraries
3. Open the Jupyter Notebook
4. Run the cells sequentially to reproduce the analysis

The notebook will load the dataset, perform exploratory analysis, build the regression model, and generate all visualizations.

---
## Future Work

Possible extensions of this project include:

- Testing more advanced machine learning models
- Feature selection to identify the most influential variables
- Exploring causal relationships between lifestyle behaviors and mental health outcomes
- Applying the workflow to real-world datasets

---

## Author

Sam Crook  
Information Systems Student | Data Science Learner