
The goal of this analysis will be the evaluation and optimal selection of different linear regression models on the Credit.csv dataset.

The Credit.csv dataset from Tbishirani's book contains n = 4000 observations of 11 variables related to n cardholders. 

The response variable is Balance (average credit card debt balance for each individual).
The quantitative variables are as follows: 

- Age, 
- Cards (number of credit cards),
- Education (years of education), 
- Income (in thousands of dollars), 
- Limit (credit limit granted),
- Rating (credit rating held).

Qualitative variables are: 

- Own (home ownership or not: Yes/ No),
- Married (married status or not: Yes/ No),
- Student (student status or not: Yes/ No),
- Region (Region of the U.S.: West, East, South).
  
The project consists of an initial part in which the inclusion of qualitative variables is evaluated through the creation of dummies variables.

Then some simple multivariate models with qualitative and quantitative variables together are analyzed, the possible collinearity between variables is analyzed, and the impact of including interaction variables and polynomial variables (degree >1) is evaluated.

Finally, an attempt is made to indicate an optimal model based on some indirect estimates of model error such as AIC , BIC and Cp, implementing the methods of forward stepwise selection and best subset selection.




