# Kaggle
All my code for kaggle competittions.

# Goals for Titanic project
The main focus is feature engineering.

## Base dataset
- Simple dataset with some easy manipulations to check a base score.

## Advanced dataset
- More research on the features like combining features, extracting certain values from columns, second order feature enginneering etc...

## Lasso with crossvalidation and report 
- A quick and easy method to check if some features have any importance.
- Easy report function too look at the coefficients between multiple splits of crossvalidation.
- Plot function to show how much a specific coeficient changes for different c values.

## Correlation matrix ideas
- For every feature we want somewhat correlation with the target.
- Every feature should not have too much correlation with other features.
- Even IF there is not too much correlation between features there maybe some "leaked" correlation if two (n) features combined have high correlation. (I have to make a method to research this.) 
UPDATE:
- We can use pca component analysis for this problem! I have to learn it a bit but the main idea is when you have 2 correlated features they sometimes have the same "information" we want to keep the information in the featureset but we dont want them to exist in multiple features. 
- We can also use common sense if we don't want to bother with this like "How can I extract the common information and include it into a different feature"