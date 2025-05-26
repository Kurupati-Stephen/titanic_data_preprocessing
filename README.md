🚢 Titanic Dataset - Data Cleaning & Preprocessing
This project focuses on cleaning and preparing the Titanic dataset for machine learning applications. It covers all essential data preprocessing steps.

🔧 Steps Followed:
Import Libraries & Dataset
Loaded the Titanic dataset using Pandas and explored it using .head(), .info(), and .isnull().sum() to understand structure and missing values.

Handle Missing Values

Filled numerical columns with the mean.

Categorical columns were filled with their mode (most frequent value).

Encode Categorical Features
Used One-Hot Encoding (pd.get_dummies) to convert categorical variables into numeric form.

Standardize Numerical Features
Applied StandardScaler from sklearn to normalize all numerical columns.

Outlier Detection & Removal

Plotted boxplots using Seaborn to visualize outliers.

Removed outliers using the IQR (Interquartile Range) method.

Final Output

Displayed the cleaned dataset using .head() and .shape()

Saved and deployed the notebook to GitHub.

🚀 Deployment
The complete notebook was saved using Jupyter Notebook (.ipynb) format.

It was uploaded to this GitHub repository via the Upload files feature.

All preprocessing code, visualizations, and comments are included for easy understanding.
