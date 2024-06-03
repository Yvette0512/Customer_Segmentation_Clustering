# Customer Segmentation for Grocery Firm

## Project Overview

This project focuses on unsupervised clustering of customer records from a grocery firm's database. By segmenting customers into distinct clusters based on similarities in their data, this project helps in tailoring products and marketing strategies to meet the unique needs and behaviors of different customer groups.

## Methodology

### Data Preparation

The customer data was cleaned and preprocessed to ensure the quality and integrity of the analysis. This involved handling missing values, normalizing data, and encoding categorical variables as necessary.

### Dimensionality Reduction

Dimensionality reduction was performed to reduce the number of random variables under consideration, by obtaining a set of principal variables. This step helps in simplifying the model while retaining the significant information.

### Clustering

Agglomerative clustering was used to segment the customer data into four distinct clusters. This hierarchical clustering technique was chosen for its effectiveness in identifying the hierarchical structure of data points.

### Customer Profiling

Each cluster was analyzed to identify common characteristics within the group, such as family structure, income, and spending habits. This profiling assists in understanding the specific needs and preferences of each segment.

## Results

The clustering process successfully categorized customers into four key segments. These segments were profiled based on demographic and behavioral data, providing valuable insights into different customer types within the grocery firm's market.

## Usage

To run the clustering analysis, follow these steps:

1. **Prepare your environment**:
   - Ensure Python 3.x is installed.
   - Install necessary libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`.

2. **Set up the data**:
   - Place the customer data file in the `data/` directory.

3. **Run the analysis**:
   - Execute the main script via the command line: `python customer_segmentation.py`
   - The script will perform data preprocessing, dimensionality reduction, clustering, and profiling automatically.

## Future Work

Further analysis could refine the clusters and explore additional variables for segmentation. The integration of machine learning models to predict customer behavior based on the identified segments could also enhance the business strategy.

## Contributions

Contributions are welcome. Please fork the project, make changes, and submit a pull request for review.
