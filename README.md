# 🧠 Stroke Prediction Analysis

## 📊 Project Description

This project performs an exploratory and predictive analysis on risk factors associated with strokes. The main goal is to identify patterns and key characteristics that might influence stroke risk and to build a basic predictive model using Logistic Regression.

## 📂 Data Source

The dataset used for this analysis was sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). It contains demographic and clinical information about patients, such as age, hypertension, heart disease, glucose levels, and body mass index (BMI).

## 🎯 Objectives

- 🔍 Explore the data to understand the demographic and clinical characteristics associated with stroke patients.
- 🔗 Identify correlations and patterns between variables and stroke occurrences.
- 🛠️ Build a predictive model using Logistic Regression to estimate stroke risk based on the available factors.
- 📝 Communicate key insights and recommendations for stroke prevention based on the results of the analysis.

## 🧑‍💻 Project Structure

1. **Data Loading and Cleaning**:
   - 🧹 Check for missing values.
   - 🔄 Handle and convert categorical variables.
   - 📋 Describe continuous and categorical variables.

2. **Exploratory Data Analysis (EDA)**:
   - 📊 Examine the distribution of variables such as age, glucose levels, and BMI.
   - 🧮 Analyze the distribution of strokes among different groups (e.g., patients with or without hypertension).
   - 📈 Create visualizations such as histograms, boxplots, and heatmaps to explore correlations between variables.

3. **Predictive Modeling**:
   - 🧠 Apply Logistic Regression to predict stroke occurrence based on the available variables.
   - 📊 Evaluate model coefficients and interpret the results.

4. **Conclusion and Recommendations**:
   - ✔️ Identify significant factors contributing to stroke risk (e.g., hypertension, heart disease, and elevated glucose levels).
   - 📢 Provide recommendations for preventive actions, such as monitoring high cardiovascular risk patients.

## 🛠️ Key Tools Used

- **Python**: Primary programming language for the analysis.
- **Libraries**:
  - 🐼 `Pandas`: For data manipulation and analysis.
  - 📊 `Matplotlib` and `Seaborn`: For data visualizations.
  - 🧠 `Scikit-learn`: For building and evaluating predictive models.

## 🔍 Results

The main findings of the analysis indicate that factors such as advanced age, hypertension, heart disease, and elevated glucose levels are associated with an increased risk of stroke. However, the logistic regression model explained only about **8.56% of the variance** (Pseudo R-squared), suggesting that other factors not included in this dataset might also contribute to stroke risk, and further data collection would be beneficial for improving the prediction.

## 🚀 Future Improvements

- ⚙️ Explore other machine learning models, such as **Random Forest** or **XGBoost**, to improve predictive accuracy.
- 🔍 Incorporate additional data that could impact stroke risk, such as family history or other clinical indicators.
- ⚖️ Use class balancing techniques to address any class imbalance issues (if there are significantly more examples of patients without stroke than with stroke).


## 📄 Dataset

The dataset used in this project is publicly available on [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).

