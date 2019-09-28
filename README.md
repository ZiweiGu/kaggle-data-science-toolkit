# Standard Data Science Toolkit
A set of scripts commonly used for data analysis. They can become handy in a data challenge, competition or any data science project. Preferred inputs and outputs to work with are **Pandas DataFrames**.

Tools included:
## Exploratory Data Analysis (EDA)
- A function that plots all the variables against the label (a great starting point)


## Data Preprocessing
- A function that bins continuous variables into classes. 
- A function for dataset augmentation in the case of imbalanced datasets


## Feature Engineering
- A function that extracts info from dates.
- A function that vectorizes text data (tf-idf, word embeddings, etc.)


## Model Building
-- supervised models -- 
- A function that builds the ROC curve and optimizes the cutoff point.
- A function that cross-validates.
- A function that returns partial dependence plots for the top random forest variables. 
- A function that builds a decision tree and automatically extracts the top 3/4 splits.

-- unsupervised models -- 
- A function that performs PCA and K-means on a dataframe (finding optimal # of components - plotting on 2-d plane - finding optimal # of clusters - clustering)

## Parameter Tuning

## Model Ensembling
- A function that stacks multiples models (should be the root of the training-validating pipeline)
