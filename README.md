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
 ## View the generated plots and insights.
 ![output_13_0](https://github.com/user-attachments/assets/c4ca7b47-b84d-4d2e-bac0-25571035b026) 
 ![output_26_0](https://github.com/user-attachments/assets/37094364-6838-4f6b-b323-c8629e04d018)


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

