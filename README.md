# Titanic Survival Analysis & Exploratory Data Analysis (EDA)

## Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover survival patterns based on **age, gender, passenger class, fare, and family size**. Using **Python, Pandas, Matplotlib, and Seaborn**, it provides meaningful insights with visualizations.

## Dataset
- **Source:** Titanic dataset (`titanic.csv`)
- **Columns Used:**
  - `Survived` - Survival status (0 = No, 1 = Yes)
  - `Pclass` - Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
  - `Sex` - Gender of the passenger
  - `Age` - Age of the passenger
  - `Fare` - Ticket fare price
  - `SibSp`, `Parch` - Family relationships on board

## Objectives
- Clean and preprocess data (handle missing values)
- Perform **univariate, bivariate, and multivariate analysis**
- Identify survival factors through **data visualization**
- Find patterns like survival rate by **class, age, gender, fare, and family size**

## Installation & Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas matplotlib seaborn
```

## How to Run the Project
1. Place `titanic.csv` in the same directory as the Python script.
2. Run the Python script:
   ```bash
   python titanic_eda.py
   ```
3. View the generated plots and insights.

## Key Visualizations
1. **Survival Rate by Passenger Class** → Higher survival rate in **1st class**.
2. **Age vs Survival Trend** → **Children had better survival chances**.
3. **Survival Rate by Gender** → **Women had significantly higher survival rates**.
4. **Fare Influence on Survival** → **Higher fares correlated with increased survival rates**.
5. **Family Size Impact** → **Passengers with family had better survival chances**.
6. **Feature Correlation Heatmap** → Shows relationships between numerical variables.

## Example Plots
The following plots are included in the analysis:
- **Histogram for Age Distribution**
- **Bar Plot for Passenger Class**
- **Boxplot for Fare vs Survival**
- **Heatmap for Feature Correlation**
- **KDE Plot for Survival by Age**
- **Survival Rate by Gender and Family Size**

## Conclusion
The analysis confirms survival was influenced by:
- **Economic status (Pclass)**
- **Age and gender prioritization**
- **Fare amount and wealth**
- **Traveling alone vs with family**

For further improvements, predictive modeling could be added to **predict survival probabilities**!

## Author
- **Om**
```

---
