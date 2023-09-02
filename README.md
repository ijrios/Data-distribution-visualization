# Distribution Visualization and Principal Component Analysis (PCA)

When working with multivariate databases, it is important to review the data distribution in each variable. Additionally, when dealing with a dataset where classifying observations is crucial, it is highly useful to validate which variables provide better discrimination of the classes. For this purpose, visualizing the distributions is of great utility.

https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction

This work is carried out with the database from the previous link:

Exercise (To be submitted by September 5th):

The database has 96 columns, with the first one corresponding to the target variable (Bankrupt?), and the other 95 columns are variables that allow us to perform the analysis to classify companies.

Perform an analysis using Boxplots to decide which variables provide better discrimination between class 0 and 1. Select 6 variables. Use Seaborn's pairplot.

With the selected variables, create scatterplots and visually check bivariate distributions using pairplot.

Implement PCA on these 6 variables and validate if it can work in 2 dimensions. Create scatterplots for the first two principal components and probability contour plots. Check on the heatmap which variables each principal component uses.

### About Dataset

Context
- The data were collected from the Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy was defined based on the business regulations of the Taiwan Stock Exchange.

