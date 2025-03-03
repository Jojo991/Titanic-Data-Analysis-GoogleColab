# Titanic-Data-Analysis-GoogleColab
Analysis Performed:
Survival Rate by Gender:

I calculated the survival rate for each gender using groupby('Sex') and mean() on the 'Survived' column.
The analysis revealed that females had a significantly higher survival rate compared to males.
Survival Rate by Passenger Class:

Using groupby('Pclass') and calculating the mean of 'Survived', I observed that first-class passengers had the highest survival rate, followed by second-class and third-class passengers.
Average Age of Survivors and Non-Survivors:

I calculated the average age of survivors and non-survivors by grouping the data by 'Survived' and calculating the mean of the 'Age' column.
The results showed that survivors were, on average, younger than non-survivors.
Data Visualization:
Survival Rate by Gender:

I visualized the survival rates by gender using a bar chart. The plot confirmed that women had a significantly higher survival rate compared to men.
Survival Rate by Passenger Class:

I created another bar chart to show the survival rate by passenger class. It confirmed that first-class passengers had the highest survival rate, followed by second and third-class passengers.
Age Distribution of Survivors and Non-Survivors:

A histogram was plotted to compare the age distribution of survivors and non-survivors. This visualization indicated that survivors were generally younger compared to non-survivors.
Additional Insights:
Survival Rate by Embarked Location:

I explored survival rates based on the embarkation location ('Embarked') and found that passengers who boarded in Cherbourg had the highest survival rate, which was visually confirmed by a bar plot.
Survival Rate by Age Group:

I categorized passengers into different age groups using pd.cut() (e.g., '0-12', '13-20', '21-40', etc.). By grouping the data based on these age groups and calculating the survival rate, I found that children (ages 0-12) had the highest survival rate.
