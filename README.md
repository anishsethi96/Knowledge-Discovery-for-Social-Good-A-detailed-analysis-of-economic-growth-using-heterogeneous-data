# Knowledge Discovery for Social Good: A detailed analysis of economic growth using heterogeneous datasets
## Abstract
Education is one of the foremost indicators of a country's growth. It is also vastly dependent on various factors specific to certain regions and their economic growth. This project focuses on analysing data on education, economic development indicators, unemployment, gender, and age disparity in various industries to find trends and correlations that help in understanding economic growth in countries better. During our research, we factored in various indicators for over 15 countries across the globe from data collected by the United Nations and the World Bank. We observed that education is a significant positive indicator of direct and indirect economic growth since an increase in education quality leads to better employment and eventually increases a country's Gross Domestic Product (GDP). Initial analysis included previous research on UN datasets intended to find the effects of primary, secondary, and tertiary education on growth, specifically the GDP and the individual Gross Value Added (GVA) by various sectors. Our analysis depicts the relation between education and growth for regions worldwide and certain countries of interest (e.g. United States of America, India, China, Greece, and Syria). A Linear model was applied to predict the GDP and growth of individual countries based on the enrolment in tertiary school and the changing value-added by sectors. KNN Classification was done on the countries to classify them into three broad categories of Low, Average, and High levels of GDP based on the linear model. The datasets used during the analysis contained information from over 200 countries for the past 50 years starting from the 1970s and consisted of some missing values for specific years. The missing values where taken care of using the common point imputation method. Due to the nature of the multiple indicators used, all the datasets did not follow a uniform format and needed to be formatted to conform to a uniform structure. The data was compiled by the United Nations and the World Bank, and it contains data on GDP per capita of nations, school enrolment in primary, secondary and tertiary education based on gender, gross national incomeand government consumption. This paper depicts the relation between education, growth, employment and trade based on various factors including age and gender for regions around the world including countries from Nordic nations, European, South Asian Association for Regional Cooperation (SAARC) nations and Sub-Saharan African nations. We conducted the Exploratory Data Analysis (EDA) to gain meaningful insights prior the conduct the in-depth analysis and the analysis is done using R and Python programming languages. We utilized several clustering methods, such as Agglomerative clustering, MeanShift clustering, and Birch clustering in our analysis. We also utilized dimensionality reduction techniques such as Principal Component Analysis (PCA) to lower the dimension and find the two most correlated principal components that would act as a basis for clustering on countries growth in a specific year. Hierarchical Clustering was implemented using the Ward variance minimization algorithm whose results were plot in the form of a dendrogram to identify optimal number of clusters. For 3 clusters, we were able to see that countries were clustered according to their GDP of High, Medium and Low.

**Index Terms** — Education, Growth, Economy, Unemployment, Gender Parity, Agglomerative Hierarchical Clustering, Birch Clustering, Mean Shift Clustering, KNN Clustering, Principle Component Analysis, Sustainable Development Goals, Social Good, Knowledge Discovery, Data Engineering

<img src="https://github.com/anishsethi96/ICDE-Economic-Growth/blob/main/Workflow%20diagram%20growth.png?raw=true" alt="workflow diagram" width="600" />
