# Customer Segmentation Using Clustering

## Project Overview
This project aims to perform customer segmentation using clustering techniques based on purchasing behaviors and demographic characteristics. We utilized a dataset from a marketing campaign to uncover distinct customer segments, which will aid in developing targeted marketing strategies.

## Project Workflow
1. **Data Loading**: Load the data and inspect its structure.
2. **Preprocessing**: Handle missing values, outliers, and format data.
3. **Exploratory Data Analysis (EDA)**: Visualize customer features and spending patterns.
4. **Feature Engineering**: Create new features to enrich the dataset.
5. **Clustering**: Apply clustering techniques to segment the customers.
6. **Evaluation**: Analyze the resulting clusters and their profiles.|

## Objectives
The primary objective of this project is to identify distinct groups of customers using clustering algorithms. We focus on understanding the following:
- Customer purchasing patterns and preferences.
- Demographic factors influencing purchasing behavior.
- Insights to inform marketing strategies tailored to each segment.

## Dataset
The dataset for this project was obtained from Kaggle. You can access it [here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).


## Methodology
1. **Data Collection and Preprocessing**
   - Cleaned and normalized the dataset by handling missing values, removing outliers, and scaling features.
2. **Feature Engineering**
   - Derived features such as `Age`, `Total Spending`, and `Family Size` to enhance the dataset for clustering analysis.
3. **Exploratory Data Analysis (EDA)**
   - Visualized relationships and patterns in the data using histograms, scatter plots, and correlation matrices to gain insights into customer behavior.
4. **Clustering Techniques**
   - Implemented K-Means and hierarchical clustering algorithms.
   - Determined the optimal number of clusters using the Elbow Method and silhouette analysis.
5. **Cluster Profiling**
   - Analyzed and interpreted each cluster's characteristics, helping to develop targeted marketing strategies for each group.

## Results
Cluster profiles were created based on various features, such as income, spending, age, family size, and engagement with promotions. Visualizations were generated to display cluster distributions and spending behavior, including:
- 3D projections of clusters.
- Spending vs. income profiles per cluster.
- Distribution of accepted promotions among clusters.

The clustering analysis identified several key customer segments:
- **Cluster 0**: Younger families with limited income and spending habits.
- **Cluster 1**: Middle-income families with teenagers, balancing moderate spending.
- **Cluster 2**: Affluent couples or individuals, characterized by high income and spending.
- **Cluster 3**: Established families with a range of spending habits.

Each segment offers unique insights into customer needs and spending behaviors, allowing for more precise and effective marketing efforts.



## Technologies Used
- Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Use the Code
1. Clone this repository.
2. Install the required Python libraries.
3. Run the `customer_segmentation.ipynb` notebook to execute the clustering process and view the results.
4. Visualize the customer segments and analyze the insights for targeted marketing strategies.

## Conclusion
This project demonstrates the effectiveness of clustering techniques in identifying meaningful customer segments based on purchasing behavior and demographics. By leveraging these insights, businesses can enhance customer satisfaction, optimize marketing resources, and drive profitability.

