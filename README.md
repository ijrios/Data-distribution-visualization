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

Based on the provided information and analysis, we can draw the following conclusions:

1. **Variable Selection for Discrimination:** The analysis begins by systematically categorizing variables into various groups to identify those that can effectively discriminate between classes 0 and 1. This is a critical step in any classification task to select the most informative features.

2. **Boxplots for Discrimination:** Boxplots are used to assess which variables exhibit significant differences in means between classes 0 and 1. This initial examination helps identify promising variables for discrimination.

3. **Scatterplots and Bivariate Distributions:** After selecting six key variables, scatterplots are created to visualize the relationships between pairs of variables. This allows for the observation of patterns and trends in the data, which can be essential for understanding the relationships between variables.

4. **Principal Component Analysis (PCA):** PCA is employed to reduce the dimensionality of the data and to explore whether it can be effectively represented in two dimensions. The scree plot shows that the first two principal components explain a significant portion of the data variance, making them suitable for visualization.

5. **Visualization of PCA Results:** Scatterplots are generated for the first two principal components to visualize the data in a reduced-dimensional space. This visualization helps assess whether the data can be effectively separated in this lower-dimensional representation.

6. **Feature Weight Heatmap:** A heatmap is created to visualize the contribution of original features to each principal component after PCA. This provides insights into which features play a more significant role in the data representation.

7. **Interrelation and Lack of Separation:** Despite the significant differences in means observed in boxplots, the visualization in feature space does not clearly show a notable separation between classes. This suggests that while individual variables may discriminate well, the overall distribution in feature space may be complex and interrelated.

8. **Context of the Dataset:** The analysis is performed on a dataset related to company bankruptcy prediction, collected over several years from financial sources. Understanding the context of the data is crucial for interpreting the results correctly.

In summary, the analysis combines exploratory data visualization techniques, variable selection, and dimensionality reduction with PCA to gain insights into the dataset's structure and its potential for discriminating between classes. While individual variables show promise, the overall distribution of data in feature space may pose challenges in achieving clear separation between classes, highlighting the need for further analysis and potentially more advanced modeling techniques.
