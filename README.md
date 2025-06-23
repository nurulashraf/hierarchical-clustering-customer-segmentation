# Customer Segmentation using Hierarchical Clustering

This project applies **Hierarchical Clustering** to group customers based on their demographic attributes and spending behaviour. The goal is to help businesses better understand customer patterns and tailor marketing strategies for each group.

---

## Project Structure

- **`data/`**: Contains the dataset used for analysis and prediction.
- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`requirements.txt`**: List of required Python packages
- **`LICENSE`**: MIT License file
- **`README.md`**: Project overview and usage instructions.

---

## Features

- Loads and explores customer data.
- Visualises customer distributions using scatter plots and dendrograms.
- Applies Hierarchical Clustering (Agglomerative) for customer segmentation.
- Uses Elbow and Dendrogram methods to determine the optimal number of clusters.
- Plots the segmented clusters for easy interpretation.

---

## Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Scipy

---

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/nurulashraf/hierarchical-clustering-customer-segmentation.git
    cd customer-segmentation-hierarchical-clustering
    ```

2. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn scipy
    ```

3. Place your dataset (`cleaned_retail_data.csv`) in the `data` folder.

4. Open the notebook:
    ```bash
    jupyter notebook hierarchical_clustering_customer_segmentation.ipynb
    ```

5. Run the cells and explore the analysis.

---

## License

This project is licensed under the [MIT License](LICENSE).
