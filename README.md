This dataset inlcudes columns like Age, Sex, Gender, Survival, PClass, Name etc. My task was to predict whether the passengers will survive 
or not and what are the important factors.
First I checked the shape of the data, datatypes in the dataset, checking null values. Then I have imputed all the null values using median 
and categorical columns using mode. Treated outliers using capping method. EDA analysis was performed- Univariate analysis, Bivariate Analysis and Multivariate analysis.
Dropping the unnecessary columns such as cabin, AgeGroupetc. Model Building was done by using various models such as Logistic Regression, Random Forest,
K nearest neighbour, Decision tree..Hyperparameter tuning was performed using Randomized Search CV.Out of which Random forest classifier gave the best performance(86%).
