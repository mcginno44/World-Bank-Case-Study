# World-Bank-Case-Study
Using a dataset derived from the World Bank Development Indicators, containing a variety of social, economic, and environmental metrics, this case study seeks to develop a small number of new “development archetypes” that summarize broad global patterns in national progress. The traditional groupings (“developed” and “developing”) are simplistic and may fail to capture new trends. 

As a result, this case study will transcend these traditional groupings and forge new ones. The analysis is carried out using economic data derived from the World Bank Development Indicators, containing a variety of social, economic, and environmental metrics, The sections contained in the pdf file discuss the initial data analysis, the steps in the process of cleaning the data, simplifying the number of predictors, and clustering the countries to obtain these new groupings in the Methods Section. Each plot included is fully interactive and able to be downloaded. Finally, there is a detailed discussion of the groups themselves in the Discussion section. 

Methodology
-1. Data Cleaning & Preparation
Handled missing values and inconsistencies across countries
Standardized variables to ensure comparability
Filtered and validated indicators for analytical relevance
-2. Dimensionality Reduction
Applied Principal Component Analysis (PCA) to:
Reduce feature space
Identify the primary drivers of variation across countries
Improve clustering performance and interpretability
-3. Clustering
Used K-means clustering to segment countries
Determined optimal number of clusters using the elbow method
Final model grouped countries into 9 distinct development archetypes
