# Online Retail Data Clustering

## About the Project

This project aims to analyze and cluster customers based on online retail data, providing valuable insights for business decision-making. The project is implemented in Python and primarily uses the `KMeans` algorithm for clustering analysis.

## Required Libraries
The following Python libraries are required for this project:

- `pandas` - For data manipulation.
- `numpy` - For numerical operations.
- `matplotlib` - For data visualization.
- `seaborn` - For enhanced plotting.
- `sklearn` - For clustering and machine learning algorithms.

To install the required libraries, run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Project Structure

The project consists of the following key steps:

1. **Data Loading and Cleaning:**
   - The data is loaded from a CSV file.
   - NaN values and negative sales values are removed.

2. **Exploratory Data Analysis (EDA):**
   - Statistical analysis of the data.
   - Identifying patterns through visualizations.

3. **Clustering Analysis:**
   - Customers are clustered using the `KMeans` algorithm.
   - Optimal cluster count is determined using the `elbow method`.

4. **Visualization of Results:**
   - Clusters are visualized in 2D and 3D plots.

## How to Run the Project

1. Place the data file (`online_retail.csv`) in the project directory.
2. Run the following command to launch the project:

```bash
jupyter notebook online-retail-data-clustering.ipynb
```

3. Execute each cell in the Jupyter Notebook sequentially.

## Outcomes
This project enables the clustering of customers to identify:

- Who are the most valuable customers?
- Which customer groups contribute the most to sales?
- Strategies for effective product targeting.

## Future Work
The project can be further extended with the following enhancements:

- Applying additional machine learning algorithms.
- Adding automated reporting functionality.
- Testing with larger and more diverse datasets.

## Contact
If you have any questions or suggestions, feel free to reach out!
