# Clustering
The objective of forming clusters based on global development measurement data is to uncover meaningful patterns and group countries or regions with similar characteristics or development profiles. Clustering, a technique widely used in data analysis and machine learning, helps partition a dataset into subsets (clusters) based on similarities or distances between data points.

To achieve this objective, several steps are typically undertaken:

     - Read the data
     - EDA(Exploratory Data Analysis)
         - Remove symbols
         - Finding missing value
         - Detecting skewness
         - Detecting Outliers - boxplot, Histogram
         - Imputations like mean, median
         - Correlation - Heatmap
         - Visualization based on the target variable - Barplot
      - Hopkins test
      - MinMax Standardization
      - Agglomerative clustering- with and without PCA
      - kmean - with and without PCA
      - Training and testing 
      - Random forest

- ## Data preprocessing:
  Basic analysis is performed to gain an understanding of the data, such as describing the dataset, handling missing values by filling them appropriately, removing symbols or unnecessary characters, and dropping irrelevant columns. Outliers may also be detected and addressed.

- ## Data visualization:
  Heatmaps and histograms are employed for visualizing the data. Heatmaps provide a graphical representation of the relationships between variables, while histograms help understand the distribution of specific features.

- ## Identifying significant countries:
  Through analysis, the top 30 countries with high and low GDP, tourism, and energy usage can be detected. This allows for the identification of outliers or countries of particular interest for further examination.

- ## Clustering techniques: 
  Different clustering algorithms can be applied to the preprocessed data. Two commonly used methods are Agglomerative Hierarchical Clustering and K-Means Clustering. These algorithms group countries or regions based on similarities in their development profiles, enabling the identification of clusters that share similar characteristics.

- ## Clustering evaluation: 
  To assess the quality of the clustering results, a measure like the Hopkins Test can be employed. This test quantifies the clustering tendency of the dataset. Additionally, standardization techniques like MinMaxScaler may be applied to ensure fair comparisons between variables.

- ## Modeling:
  Depending on the analysis goals, various modeling techniques can be employed. For instance, Random Forest classification can be utilized to build a predictive model based on the clustered data. This model can help understand the factors contributing to the different development profiles observed in the clusters.

- ## Deployment and presentation:
  Finally, the results and insights obtained from the analysis can be shared using interactive tools like Streamlit. This allows for easy and accessible deployment, enabling others to explore the findings and gain valuable insights from the data.

By following these steps, the analysis aims to uncover meaningful patterns and provide insights into the development profiles of different countries or regions. The resulting clusters can inform decision-making to promote sustainable development worldwide.





