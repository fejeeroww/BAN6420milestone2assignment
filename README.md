# BAN6420milestone2assignment
# Anderson Cancer Center Principal Component Analysis 

  

This project aims to develop a model to address the growing number of referrals at the Anderson Cancer Center. The first step is to identify essential variables for securing donor funding using Principal Component Analysis (PCA). 

  

## Project Overview 

  

1. **PCA Implementation**: We use PCA to demonstrate how essential variables can be acquired from the breast cancer dataset available from sklearn.datasets. 

  

2. **Dimensionality Reduction**: The dataset is reduced to 2 PCA components for visualization and further analysis. 

  

3. **Logistic Regression**: We implement logistic regression for prediction using the reduced dataset. 

  

## Requirements 

  

- Python 3.7+ 

- NumPy 

- Pandas 

- Matplotlib 

- Scikit-learn 

  

## Usage 

  

1. Ensure all required libraries are installed. 

2. Run the Jupyter notebook ipynb file`. 

  

## Output 

  

The notebook performs the following tasks: 

  

1. Loads and preprocesses the breast cancer dataset. 

2. Applies PCA to the dataset and visualizes the explained variance ratio. 

3. Reduces the dataset to 2 PCA components and visualizes the data in 2D space. 

4. Implements logistic regression on the reduced dataset. 

5. Evaluates the model's performance and prints the classification report. 

6. Identifies and prints the most important features based on PCA components. 

  

## Interpretation 

  

- The PCA plot shows how much variance is explained by each principal component. 

- The 2D scatter plot visualizes how well the two main components separate the classes. 

- The logistic regression results demonstrate the model's performance in predicting cancer diagnoses. 

- The list of important features helps identify which variables are most crucial for securing donor funding. 

  
