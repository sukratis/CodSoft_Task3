## Description

The provided code conducts exploratory data analysis (EDA) and prediction tasks using the Iris dataset.

### Exploratory Data Analysis
- Loads the Iris dataset using `pandas`.
- Displays basic information about the dataset.
- Modifies the 'species' column to remove 'Iris-' prefix.
- Generates descriptive statistics for the dataset.
- Visualizes data using various plots:
  - Line plots for sepal length/width and petal length/width.
  - Pair plots to visualize pairwise relationships between features.
  - Pie chart to show the distribution of species.
  - Scatter plots to compare sepal length vs. sepal width and petal length vs. petal width.
  - Box plots for sepal length and sepal width by species.
  - Density distribution plots for sepal length, sepal width, petal length, and petal width.

### Training and Testing Model
- Divides the dataset into training and testing sets.
- Applies logistic regression for classification.
- Predicts the species labels using the trained model.
- Evaluates the model accuracy using the test set.

The code provides insights into the Iris dataset's characteristics and demonstrates a simple classification task using logistic regression.
