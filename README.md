
datafun-06-eda
Project Overview

This project is part of Module 6: Exploratory Data Analysis (EDA).
The goal is to practice data exploration, visualization, and narrative storytelling using Python, Jupyter, and common data science libraries.

The dataset used for this project is the Iris dataset, a classic dataset in machine learning and statistics. It contains 150 samples of iris flowers with 4 numerical features and 1 target column indicating species.

Setup Commands

To set up this project on your machine:

# Clone the repository
git clone https://github.com/batyrovbahrom96-svg/datafun-06-eda.git

# Move into the project folder
cd datafun-06-eda

# Create and activate a virtual environment
python -m venv .venv
.venv\Scripts\activate   # On Windows
source .venv/bin/activate # On Mac/Linux

# Install dependencies
pip install -r requirements.txt

Dataset

Source: Iris Dataset - UCI Machine Learning Repository

Features:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Species (Setosa, Versicolor, Virginica)

The dataset is clean, with no missing values, and is ideal for practicing exploratory data analysis.

Key Visualizations

The notebook (bakhrom_eda.ipynb) contains multiple visualizations:

Histograms – Show the distribution of each numerical feature.

Pairplots – Highlight species differences and correlations.

Boxplots – Compare sepal and petal measurements across species.

Violin plots – Show distribution and density of features per species.

Heatmap – Display correlations between numerical features.

Findings

Setosa species is clearly separated from the others, especially by petal size.

Versicolor and Virginica overlap in some features but can still be distinguished with petal length and width.

Petal length and petal width are highly correlated (0.96) and serve as strong predictors for species classification.

Sepal width has weak or negative correlations with other features.

Final Conclusions

The Iris dataset confirms that petal features are the most discriminative among the three species.

Visualizations provide clear evidence of species clustering and correlation patterns.

This project demonstrates the standard process of performing EDA with Python, Jupyter, and libraries like Pandas, Seaborn, and Matplotlib.
