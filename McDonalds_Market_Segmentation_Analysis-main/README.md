# McDonald's Market Segmentation Analysis

This repository contains code and data for conducting a market segmentation analysis of McDonald's customers using clustering techniques. The analysis includes data preprocessing, exploratory data analysis (EDA), Principal Component Analysis (PCA), K-Means clustering, and visualization of the clustering results.

## Project Structure

```
McDonalds_Market_Segmentation_Analysis/
│
├── data/
│   └── mcdonalds.csv        # The dataset used for analysis
│
├── notebooks/
│   └── McDonalds_Segmentation.ipynb  # Jupyter notebook with the complete analysis
│
├── README.md                # Project README file
│
└── requirements.txt         # List of Python packages required for the project
```

## Dataset

The dataset `mcdonalds.csv` contains various attributes of McDonald's customers, including their demographic information and their opinions on different aspects of McDonald's food. Key columns include:

- `Gender`: Customer gender
- `Age`: Customer age
- `VisitFrequency`: Frequency of visits to McDonald's
- `Like`: Overall liking of McDonald's food
- Several columns representing opinions on food attributes such as `yummy`, `convenient`, `spicy`, etc.

## Steps in the Analysis

### 1. Data Preprocessing

- Load the dataset and display basic information.
- Check for and handle missing values.
- Check for and remove duplicate rows.
- Encode categorical variables using `LabelEncoder`.

### 2. Exploratory Data Analysis (EDA)

- Visualize the distribution of customer gender and age.
- Visualize the distribution of visit frequency and overall liking of McDonald's food.
- Visualize the distribution of opinions on various food attributes.

### 3. Principal Component Analysis (PCA)

- Standardize the data.
- Perform PCA to reduce dimensionality and identify key components.
- Analyze the explained variance ratio and cumulative variance.

### 4. K-Means Clustering

- Use the elbow method to determine the optimal number of clusters.
- Perform K-Means clustering and add cluster labels to the dataset.
- Visualize the clusters using scatter plots of the first two principal components.

### 5. Visualization of Clustering Results

- Visualize the distribution of clusters.
- Create mosaic plots to visualize the relationship between clusters and categorical variables like `Like` and `Gender`.

## Visualizations

- **Gender Distribution**: Pie chart showing the proportion of male and female customers.
- **Age Distribution**: Bar plot showing the distribution of customer ages.
- **Cluster Visualization**: Scatter plot of the first two principal components with clusters highlighted.
- **Mosaic Plots**: Mosaic plots showing the relationship between clusters and customer liking, and between clusters and gender.

## Installation

To run the analysis, you need to install the required Python packages. You can install the packages listed in `requirements.txt` using the following command:

```bash
pip install -r requirements.txt
```

## Usage

Open the Jupyter notebook `notebooks/McDonalds_Segmentation.ipynb` to view and run the analysis step by step. You can execute each cell sequentially to reproduce the results.



