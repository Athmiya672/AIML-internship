# AIML-internship
This project demonstrates the complete preprocessing pipeline for the Titanic dataset, a classic dataset used in machine learning and data science. The goal is to clean, transform, and prepare the data for modeling by handling missing values, encoding categorical variables, scaling numerical features, and detecting/removing outliers.
By following these preprocessing steps, the dataset becomes suitable for building accurate and reliable machine learning models that can predict passenger survival based on features like age, fare, sex, and embarkation port.
This workflow is essential for any real-world data science project, ensuring data quality and consistency before applying algorithms.

Technologies Used
Python
Pandas
Seaborn
Matplotlib
Scikit-learn

import pandas as pd
data=pd.read_csv("titantic.csv")
