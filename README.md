# Titanic-Survival-Analysis
  Analyzing Titanic Survivors

### Project Overview
This project explores the Titanic dataset to uncover insights into passenger survival rates. The analysis focuses on key factors such as:
-  The overall survival rate.
-  Differences in survival based on gender.
-  Variations in survival rates across passenger classes (1st, 2nd, 3rd).
-  The impact of family size on survival likelihood.
-  Additional influencing factors, including age and boarding location.

 Through this analysis, the project aims to provide a comprehensive understanding of the variables that influenced survival outcomes during the Titanic disaster.

### Data Source
The dataset for this project is the Train dataset from the Kaggle Titanic - Machine Learning from Disaster competition. It provides detailed information about a subset of Titanic passengers, including their survival status (Survived), demographics, and other attributes.

The dataset was sourced from [Kaggle](https://www.kaggle.com/competitions/titanic/data),  a platform for data science and machine learning enthusiasts.
Only the Train dataset was used in this analysis, focusing on its structured data to derive insights about survival rates across various factors.

### Tool Used
Microsoft Excel:
-  For Analysis
-  For visualization

### Dataset information
-  PassengerId: A unique identifier for each passenger.
-  Survived: Survival status (0 = Did not survive, 1 = Survived).
-  Pclass: Passenger class (1 = First class, 2 = Second class, 3 = Third class).
-  Name: Full name of the passenger.
-  Sex: Gender of the passenger (male/female).
-  Age: Age of the passenger in years.
-  SibSp: Number of siblings or spouses aboard the Titanic.
-  Parch: Number of parents or children aboard the Titanic.
-  Ticket: Ticket number.
-  Fare: Passenger fare paid for the journey.
-  Cabin: Cabin number.
-  Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

### Project Goal
-  Calculate the overall survival rate of Titanic passengers.
-  Determine how survival rates varied by gender, passenger class, and family size.
-  Visualize the findings using pivot table
-  Actionable insights from the data

### Analysis Methods
The analysis focused on exploring survival rates in the Titanic dataset using Microsoft Excel. Key steps included:
1. **Data Cleaning:**
-  Missing values in the Age column were filled with the average age.
-  The Cabin column's missing values were replaced with "Unknown."
-  Missing values in the Embarked column were filled with the most frequent value ("S").

![EXcel table](https://github.com/user-attachments/assets/3e65a5fa-d000-4648-910c-f3a0ddd39809)


  
2. **Survival Rate Calculations:**
-  Overall survival rate was determined by dividing the number of survivors by the total number of passengers.
-  Survival rates were further analyzed by gender and passenger class using conditional formulas.

![cal](https://github.com/user-attachments/assets/91847b8f-4fc1-40f0-a859-a84147cb4fa3)

  
3. **Revenue Calculation:**
-  The total ticket revenue was calculated by summing up the values in the Fare column.
  
4. **Visualization:**
-  Charts were created to visually represent survival rates by gender, class, and other factors.

![Total Revenue](https://github.com/user-attachments/assets/076ff0f1-444c-4816-9217-416329197213)

![Survival Sex](https://github.com/user-attachments/assets/894bdd96-7837-4659-a730-507aa8812615)

![survival pclass](https://github.com/user-attachments/assets/adf8a293-1aa3-4263-ab47-760710ff2f5c)

![Survival Age](https://github.com/user-attachments/assets/7f1556f9-9928-489f-b3ea-cfdd4e2d3bf6)
  

### Insights from the Analysis
1. **Overall Survival Rate:**
   The overall survival rate of 38% reveals a grim reality, there was a lack of adequate preparation for emergencies. With less than half the passengers surviving, this low survival rate highlights the insufficient availability of 
   lifeboats and safety protocols to accommodate all passengers during the disaster. It also underscores the chaos and inequality that likely influenced survival decisions.

3. **Survival Rate by Gender:**
   A striking pattern emerged in the survival rates by gender. The analysis revealed that females had a significantly higher survival rate compared to males. This suggests that the "women and children first" protocol may have been 
   followed to some extent during evacuation. However, it also highlights the disparities faced by male passengers, many of whom likely sacrificed their chance to survive for others.

5. **Survival Rate by Passenger Class:**
   Class played a significant role in survival likelihood. Passengers in First Class had the highest survival rate, followed by those in Second Class, with Third Class passengers faring the worst.
   This trend reflects the socio-economic inequalities of the time, where wealthier passengers had better access to lifeboats and safety information. The lower survival rates among Third Class passengers illustrate the tragic impact of 
   limited resources and accessibility for the less privileged.

### Conclusion
The analysis of the Titanic dataset reveals critical insights into the survival dynamics of the disaster. With an overall survival rate of 38%, it is evident that there was inadequate preparation and insufficient resources to ensure passenger safety.

Gender and socio-economic status significantly influenced survival outcomes. Female passengers had a higher survival rate, reflecting evacuation priorities of the time. Passengers in higher classes were more likely to survive than those in lower classes, highlighting the socio-economic inequalities that shaped access to safety measures.



 
