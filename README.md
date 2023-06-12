***
# OC : Food Application
***

In this project, I explore and value the content of the Open Food Facts data set to feed in an [imaginary food application](application_idea.md).

For a better and interactive navigation in notebooks, I recommend using the links below which use nbviewer instead of the GitHub notebook reader.

### [Cleansing notebook](https://nbviewer.org/github/JulienfLeBoucher/OC_food_application/blob/main/cleaning_notebook.ipynb) :
- handle duplicates and synthesize information ;
- detect outliers (unrealistic nutrients) ;
- improve/clean the classification of products ;
- impute missing values and replace outliers using KNNImputers and IterativeImputers;
- detect energy unit problems and correct it.

### [Analysis notebook](https://nbviewer.org/github/JulienfLeBoucher/OC_food_application/blob/main/exploration_notebook.ipynb):
- univariate analysis of important features.
- bivariate analysis : correlation matrix, 2D-distributions, One-way ANOVA and Kruskal-Wallis tests.
- multivariate analysis : PCA and various projections in factorial planes and 3D-spaces.
