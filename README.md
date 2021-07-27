# OpenFoodFact
"Designing an application for public health"


The Notebook 1 is for the dataprocessing. It includes the :

- Features Selection
- Drop Duplicated rows on some columns
- Data Processing on columns values
- Sampling
- NaN Imputation

  - IterativeImputer for numerical data
  - Outliers (this step has to be before the NaN Imputation)
  - SimpleImputer for categorical data brands_tags
  - linear Regression for the nutriscore_score
  - def nutrigrade_food(score) for the nutriscore_grade 
- finally distribution ckecking before and after Imputation

The Notebook 2 is for the Exploratory Data Analysis. It includes the :

- Univariate Anaysis
- Bivariate Analysis    between :
  - two quantitative variables
  - one quantitative and one categorical variable
  - two categorical variables
 - and finally, ACP with some numerical variables.

The pdf is the final presentation with some visualizations (in french).
The important idea is that we have to pay attention between the good scores A, B, C for exemple there is much more low fat product in the category C than A. 
The mean value of carbohydrates_100g is higher for the cateroy A than B and C. And if we see the category E products, half of them are less 50g / 100g in carbohydrates.  So the application would be a simple vizualizations of the products with some filters like the carbonhydrates rate, the fat rate, the nutriscore also so we can choose our product based on our priorities.
    
