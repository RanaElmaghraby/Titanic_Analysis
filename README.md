🚢 Titanic Data Analysis
📖 Overview
This project analyzes the famous Titanic dataset to explore the factors that influenced passenger survival rates.
It includes data cleaning, exploratory data analysis (EDA), visualizations, and key insights derived from the data.

📊 Dataset
Source: Kaggle Titanic Dataset

Rows: 891 passengers

Main Features: Survived, Pclass, Sex, Age, Fare, Embarked, etc.

Some columns contain missing data (e.g., Age, Embarked, Deck).

🛠️ Data Cleaning & Preprocessing
Filled missing Age values with the mean age.

Filled missing Embarked and Embark_town values with the mode (most frequent value).

Removed or handled unnecessary columns for cleaner analysis.

📈 Key Insights
Fare vs Pclass: Negative correlation → first-class passengers paid higher fares.

Survival vs Pclass: Higher survival rates for first-class passengers.

Gender & Survival:

Female survivors: 233 (68.1%)

Male survivors: 109 (31.9%)

Highest survival chance: Females in first class

Lowest survival chance: Males in second class

Fare Distribution: Most passengers paid low ticket prices.

Age Distribution: Most passengers were between 20 and 40 years old.

Female ticket fares are generally higher than male fares, with a higher median and wider price range.

🖼️ Visualizations
Histogram of Age distribution

Bar chart of Survival by Gender and Class

Heatmap showing correlations between variables

