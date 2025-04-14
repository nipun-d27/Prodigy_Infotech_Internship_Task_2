# Prodigy_Infotech_Internship_Task_2
Performing Data Cleaning and EDA (Exploratory Data Analysis) on the titanic dataset and exploring the relationships between variables and identifying patterns and trends across the data.

**Titanic Dataset Analysis – Exploratory Data Analysis (EDA)**
This project focuses on performing a comprehensive Exploratory Data Analysis (EDA) on the famous Titanic dataset to uncover insights related to passenger survival patterns. The analysis includes data cleaning, univariate, bivariate, and multivariate visualizations using Python.

**Dataset:**
The dataset contains information about the passengers aboard the Titanic, including features like age, gender, ticket fare, class, number of siblings/spouses aboard, and more. The objective is to understand the factors influencing survival.

**Data Cleaning:**
Before performing the analysis, the dataset was cleaned by handling missing values:
Age column: Missing values were filled using the median age.
Cabin column: Dropped due to a high number of missing entries.
Embarked column: Missing values were filled using the mode.

**Univariate Analysis:**
We explored the distribution of individual variables to understand their characteristics:
Survival Count – Countplot
Visual representation of the number of survivors vs non-survivors.

Age Distribution – Histplot
Histogram showing the age spread of the passengers.

Gender Distribution – Countplot
Count of male vs female passengers.

Fare Distribution – Histplot
Distribution of ticket fares paid by passengers.

Fare by Passenger Class – Boxplot
Boxplot to compare fare distribution across different passenger classes.

**Bivariate Analysis:**
We explored how pairs of variables interact, especially in relation to survival:
Survival by Siblings/Spouses Aboard – Countplot

Survival by Gender – Countplot

Survival by Passenger Class – Countplot

Survival by Embarkation Port – Countplot

Age vs Survival – Violinplot
Visualizing the age distribution for survivors and non-survivors.

**Multivariate Analysis:**
To understand how multiple variables interact, we used:
Catplot – Survival by Class and Gender
Visualizing survival rates across class and gender combinations.
Histogram – Age Distribution by Survival
Comparing age distributions between survivors and non-survivors.

**Correlation Heatmap – Numerical Features:**
A heatmap showing the correlation between numerical variables like age, fare, and survival.

**Technologies Used:**
Python (Pandas, Matplotlib, Seaborn)
Jupyter Notebook

**How to access the Dataset:**
The Dataset is attached below or can also be viewed from Kaggle.
