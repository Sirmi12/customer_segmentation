Customer Segmentation Analysis Repository

This repository contains code and resources related to a customer segmentation analysis performed using K-means clustering, Principal Component Analysis (PCA), and Exploratory Data Analysis (EDA). The primary objective of this analysis is to gain insights into customer behavior by identifying distinct segments within the customer base.
Contents:

    Notebooks:
        1_EDA.ipynb: Jupyter notebook containing the Exploratory Data Analysis (EDA) process.
        2_PCA.ipynb: Jupyter notebook demonstrating Principal Component Analysis (PCA) for dimensionality reduction.
        3_KMeans.ipynb: Jupyter notebook implementing K-means clustering for customer segmentation.

    Data:
        customer_data.csv: Raw data file containing customer information used in the analysis.

    Output:
        segmented_customers.csv: CSV file containing the segmented customer data with assigned clusters.

Usage:

    Clone the repository to your local machine:

bash

git clone <repository_url>

    Install the required dependencies:

bash

pip install -r requirements.txt

    Run the notebooks sequentially:
        Start with 1_EDA.ipynb to explore the dataset and understand its characteristics.
        Proceed to 2_PCA.ipynb to perform dimensionality reduction using PCA.
        Finally, execute 3_KMeans.ipynb to apply K-means clustering and segment the customers.

    After running the notebooks, you can access the segmented customer data in segmented_customers.csv for further analysis or downstream applications.

Requirements:

    Python 3.x
    Jupyter Notebook
    NumPy
    pandas
    scikit-learn
    matplotlib
    seaborn

Contributors:

    [Your Name] - [Your Contact Information]

License:

This project is licensed under the MIT License.
