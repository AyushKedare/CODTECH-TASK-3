Name: Ayush Kedare
Company: CODTECH IT SOLUTIONS
ID: CT08DS6458
Domain: Data Analytics
Duration: 5th August to 5th September 2024
Mentor: Muzammil Ahmed

**Objective:**
The project focuses on analyzing customer data from a mall. The goal is to understand customer demographics, behavior, and potentially segment customers based on specific criteria such as income and spending habits.

**Key Features:**
1. Data Analysis:
	Dataset Loading:
	The dataset "Mall_Customers.csv" is loaded into a Pandas DataFrame. The first few rows of the dataset are displayed using data.head(5).
	Basic Exploration:
	Data Shape: The shape of the dataset (i.e., the number of rows and columns) is checked to understand its structure.
	Statistical Description: The describe() function provides summary statistics like mean, median, standard deviation, etc., for numerical columns.
	Data Information: The info() function is used to display the data types of each column and to check for missing values.
	Missing Values Analysis: Missing values are checked using data.isnull().sum(), and a visual representation of missing data is created using the missingno library.
2. Data Visualization:
	Distribution Plots:
	Age Distribution: A distribution plot of the "Age" column is created using Seaborn's distplot function.
	Annual Income Distribution: A distribution plot of the "Annual Income (k$)" column is created to analyze the income range of the customers.
	Spending Score Distribution: A distribution plot of the "Spending Score (1-100)" column is used to understand customer spending behavior.
	Gender Distribution: A pie chart is created to visualize the gender distribution in the dataset.
	Histograms: Histograms for all numerical columns in the dataset are generated to understand their distributions visually.
	Pair Plots: A pair plot is created to visualize relationships between different numerical variables, providing insights into potential correlations.
	Count Plots: Count plots are used to show the distribution of values in categorical columns, such as Age, Annual Income, and Spending Score.
	Scatter Plots:
	Age vs. Annual Income: A scatter plot is used to explore the relationship between Age and Annual Income.
	Annual Income vs. Spending Score: A scatter plot is used to explore the relationship between Annual Income and Spending Score, differentiated by gender.
3. Machine Learning Models:
	K-Means Clustering:
	Feature Selection: The features "Annual Income (k$)" and "Spending Score (1-100)" are selected for clustering analysis.
	Elbow Method: The Elbow Method is used to determine the optimal number of clusters by plotting the sum of squared distances (inertia) for different numbers of clusters.
	Model Training: A K-Means model is trained with 5 clusters using the KMeans class from Scikit-Learn to segment the customers.
	Cluster Visualization: The clusters are visualized using a scatter plot, where different colors represent different clusters. The cluster centroids are also plotted for better interpretation.
4. Code Explanations:
	Data Processing Libraries: The notebook imports and uses libraries such as Pandas, NumPy, Matplotlib, Seaborn, and missingno for data processing and visualization.
	Visualization Libraries: Seaborn and Matplotlib are extensively used for creating various types of plots, such as distribution plots, pair plots, histograms, and scatter plots.
	Clustering Analysis: The notebook uses the Scikit-Learn library to implement K-Means clustering. The Elbow Method is applied to determine the optimal number of clusters, and the results are visualized with scatter plots.


**Tech Stack:**
	Programming Language: Python
	Libraries:
	Pandas for data manipulation.
	NumPy for numerical operations.
	Matplotlib and Seaborn for data visualization.
	Scikit-Learn for machine learning, particularly for clustering analysis.


![image](https://github.com/user-attachments/assets/cfac6ae8-16b2-4902-814d-62bf2730a15d)

![image](https://github.com/user-attachments/assets/04ce37fb-d4ec-47a9-a481-4f3228b7ed99)

![image](https://github.com/user-attachments/assets/52837d3b-19b3-4efc-8f0e-77d606476566)

![image](https://github.com/user-attachments/assets/d50b21ca-762c-4207-82cb-f42a67cec23d)

![image](https://github.com/user-attachments/assets/6449b33f-1191-41ab-951a-3efd0e63abf1)

![image](https://github.com/user-attachments/assets/c97d14d3-4048-4fbc-a280-ca87459ab924)







