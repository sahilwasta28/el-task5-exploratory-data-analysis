# 📂 Elevate Labs Data Analyst Internship - Task 5: Exploratory Data Analysis (EDA)

## 📌 Task Overview
This task, completed as part of the Elevate Labs Data Analyst Internship, focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset. The primary objective was to understand the dataset's structure, identify patterns, and prepare the data for further analysis or predictive modeling.

## ⚙️ Tools and Dataset
- **Tools Used**: Python 3.x, Golab Colab / Jupyter Notebook , Pandas, NumPy, Matplotlib, Seaborn
- **Dataset**: Titanic dataset from Kaggle

  (link - https://www.kaggle.com/c/titanic/data?select=train.csv&utm_source=chatgpt.com) 

## 📝 EDA Process and Analysis
The EDA process involved several key steps to gain insights into the Titanic dataset:

1. **Data Loading and Inspection**: Loaded the Titanic dataset and performed initial inspections to understand its structure and identify any immediate issues.
2. **Data Cleaning**: Addressed missing values by:
   - Filling missing 'Age' values with the median age.
   - Filling missing 'Embarked' values with the mode.
   - Dropping the 'Cabin' column due to excessive missing data.
3. **Data Transformation**:
   - Encoded categorical variables such as 'Sex' and 'Embarked' to numeric values for analysis.
4. **Exploratory Analysis**:
   - Analyzed the distribution of key variables like 'Age', 'Fare', and 'Survived'.
   - Investigated relationships between variables using correlation matrices.
5. **Visualization**:
   - Created various plots to visualize distributions and relationships, including histograms, bar charts, and heatmaps.

## 🔍 Key Insights and Conclusions
Through the EDA, several insights were uncovered:

- **Gender-Based Survival Rates**: Females had a significantly higher survival rate compared to males.
- **Class-Based Survival Rates**: Passengers in first class had a higher survival rate than those in second and third classes.
- **Age Distribution**: The majority of passengers were between 20 and 40 years old.
- **Fare Distribution**: A wide range of fares was observed, with a few passengers paying significantly higher fares.

These insights provide a foundation for further analysis and modeling, particularly in predicting survival rates based on passenger characteristics. For more details , refer the Findings pdf attached in the repo.  

## 🙋‍♂️ Author
- **Name**: Sahil Wasta
- **Internship Task**: Task 5 - Exploratory Data Analysis
