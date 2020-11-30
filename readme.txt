Import the necessary modules from the libraries
check the data set, variables
UNivarte
This type of data consists of only one variable. The analysis of univariate data is thus the simplest form of analysis since the information deals with only one quantity that changes. It does not deal with causes or relationships and the main purpose of the analysis is to describe the data and find patterns that exist within it. 
->the univarte analysis of age,cp-death,Platelet by seaborn distplot,to see the distibution of variable.
 ->it shown Age is a defintely a factor in fatal heart attacks.
 ->The CP Distribution plot is similar for both death event values which signifies it has lower impact on the death event.
->Death rate in higher in patients with high blood pressure

Bivarte
This type of data involves two different variables. The analysis of this type of data deals with causes and relationships and the analysis is done to find out the relationship among the two variables.Example of bivariate data can be temperature and ice cream sales in summer season.
->the plots are countplot,piechart.
->the bivarte analysis of varibles with target variable(Deathevent)
->Patients with anaemia are at a higher risk of death - 36% of patients who died had anaemia, while only 29% of the patients who are still alive have anaemia
->Higher percentage of our datset is non diabetic
->As far as fatal heart attacks are concerned we can see that diabetes does not play a part according to our sample.
->We can observe that patients with a lower ejection fraction are at higher risk
->The CP Distribution plot is similar for both death event values which signifies it has lower impact on the death event
->Compared to men, women are at greater risk from smoking
->Platelet count has lower impact on the death rate. The mean and SD for both cases where there has been a fatality and non fatality are comparable.
Outliers
->Our main output variable is deathevent,So we plotted the boxplot with deathevent vs few variables that have good correlation with it.

Machine learning models:
We used 3 types of machine learning model.
The results of each model are as follow:
Random forest: 90%
K nearest neighbour: 93.33%
Logistic regression: 86.67%
So among them KNN is preforming better .

