# PRODIGY-_DS_task2
# Titanic Dataset Analysis: Insights and Patterns  

## Project Overview  
This project explores the Titanic dataset to uncover trends, relationships, and patterns in the survival data. By performing data cleaning and exploratory data analysis (EDA), we aim to understand the factors that influenced survival rates and provide meaningful insights into passenger demographics, socioeconomic indicators, and survival probabilities.

## Dataset  
The dataset used in this project is the Titanic dataset from Kaggle:  
[Dataset Link](https://www.kaggle.com/c/titanic/data)

### Key Features:  
- **Survival:** Indicates if the passenger survived (1) or not (0).  
- **Pclass:** Passenger class (1 = First, 2 = Second, 3 = Third).  
- **Sex:** Gender of the passenger.  
- **Age:** Age of the passenger.  
- **SibSp and Parch:** Family relationships onboard (siblings/spouses and parents/children).  
- **Fare:** The ticket price paid by the passenger.  
- **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Key Insights  

### 1. Survival Rate Disparities  
- **Mortality:** Approximately 62% of passengers did not survive.  
- **Survival by Gender:** Women had significantly higher survival rates compared to men, highlighting the "women and children first" protocol.  
- **Survival by Class:** First-class passengers had higher survival odds compared to second and third-class passengers.  

### 2. Demographic Analysis  
- **Age Distribution:** The majority of passengers were aged 20-40, with survival favoring younger children (under 5 years).  
- **Family Size:** Small to medium-sized families (2-4 members) had higher survival rates, while solo travelers and large families faced lower chances of survival.

### 3. Correlations  
- **Gender and Survival:** Strong positive correlation (0.54).  
- **Class and Fare:** Higher class correlated with higher fare and better survival chances.  
- **Family Size:** Inverted U-shape pattern for survival rates, peaking at 4 members.

### 4. Port of Embarkation  
- Passengers from Cherbourg (C) had the highest survival rate (55%), while those from Southampton (S) had the lowest (34%).

## Visualizations  
This analysis includes:  
- Correlation heatmaps to identify significant relationships.  
- Age distributions and their impact on survival.  
- Survival rates by family size and embarkation point.  
- Class and gender breakdowns for survival probability.

## Conclusion  
The Titanic survival data highlights the profound impact of gender, class, and family size on survival chances. This project emphasizes the social and structural inequalities prevalent during the Titanic disaster, offering valuable insights for further historical and demographic studies.

## Getting Started  

### Prerequisites  
- Python (version 3.7 or above)  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn  

