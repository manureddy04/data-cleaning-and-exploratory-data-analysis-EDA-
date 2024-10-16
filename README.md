#Titanic Dataset Analysis
##Overview
This project explores the Titanic dataset, analyzing the factors that influenced passenger survival. The dataset includes various attributes of passengers, such as age, gender, class, and embarkation point. The goal of this analysis is to uncover patterns and insights regarding survival rates.

##Dataset
The dataset used in this project is the Titanic dataset, which can be obtained from Kaggle. The CSV file should be named titanic.csv.

##Attributes
PassengerId: Unique identifier for each passenger
Survived: Survival status (0 = No, 1 = Yes)
Pclass: Passenger class (1st, 2nd, or 3rd)
Name: Name of the passenger
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Fare paid for the ticket
Cabin: Cabin number (removed due to high missing values)
Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
##Installation
To run this project, you will need to have the following libraries installed:

#bash
##Copy code
pip install pandas matplotlib seaborn
##Usage
Clone the repository or download the files.
Place the titanic.csv file in the same directory as the Jupyter notebook or Python script.
Run the analysis code to explore the dataset and generate visualizations.
#Data Cleaning Steps
##Handle Missing Values:

Filled missing Age values with the median age.
Filled missing Embarked values with the most frequent port.
Dropped the Cabin column due to high cardinality of missing values.
##Data Type Conversion:
Converted Survived and Pclass columns to categorical types.
#Exploratory Data Analysis (EDA)
##Age Distribution: Visualized the age distribution of passengers.
##Survival Count: Count of survivors and non-survivors.
##Survival Rate by Gender: Analyzed survival rates based on gender.
##Survival Rate by Passenger Class: Analyzed survival rates based on passenger class.
##Age Distribution by Survival: Compared age distributions between survivors and non-survivors.

#Visualizations
##The following visualizations are included in this analysis:
Distribution of Age
Count of Survival
Survival Rate by Gender
Survival Rate by Passenger Class
Age Distribution by Survival
#Conclusion
This analysis provides insights into the factors influencing survival on the Titanic. The findings indicate that gender and passenger class were significant predictors of survival.

#License
This project is licensed under the MIT License.
