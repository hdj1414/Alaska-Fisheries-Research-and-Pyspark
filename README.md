# Alaska-Fisheries-Research-and-Pyspark
Enhancing Fisheries Research Insights through Big Data Analytics: Leveraging Apache Spark for Scalable and In-Depth Analysis

# Introduction
The importance of Alaska's fishing sector in the context of the United States cannot be understated. This industry is the principal source of the country's wild salmon and other valued seafood items. However, its potential is limited by difficult weather circumstances, which impose a narrow window for open-sea fishing owing to cold wintery temperatures (Sergeant et al., 2022). The short timescale emphasizes the importance of strategic management to maximize returns. Using machine learning regression analysis appears to be a critical tool in this effort. This method optimizes fish capture counts during the limited fishing season by using the power of data-driven insights. As a result, the use of cutting-edge analytical techniques becomes essential, increasing sustainability and efficiency in the Alaskan fishing business.

# Objective
The objective of this project as, to identify the best regression analysis-based model that can predict the quantity of fish per fish type that can be caught per hour or CPUE1 to understand which areas are more productive than others for preform fishing operations in the Alaskan Waters.

# Research Question
• Which regression method provides more accurate predictions compared to other regression models?
• Which method provides better prediction, among regression models or time series?
• What are the most important variables that are useful for building the regression model for predicting the number of fish caught per hour?

# Technology Used
The project involved the use of various technologies and tools for data analysis and modeling, such as:
• PySpark: Utilized for large-scale data processing, PySpark facilitated CSV file handling and distributed data exploration, feature engineering, and machine learning (Ali and Iqbal, 2022).
• Pandas and NumPy: Leveraged for data manipulation and numerical operations, Pandas handled tabular data structures, while NumPy facilitated mathematical and statistical calculations (Khatami and Frantz, 2023).
• Scikit-Learn: Employed for implementing and comparing regression models, Scikit-Learn offered metrics and tools for model evaluation, including mean squared error and cross-validation (Tran et al., 2022).
• Matplotlib: Utilized for data visualization, Matplotlib enabled the creation of various plots and charts, providing customization options for appearance and style (Chandra and Dwivedi, 2022).

Libraries Used
• pyspark.sql: Central in Spark, this library manages structured data, aiding data manipulation and transformation in distributed collections efficiently (Belcastro et al., 2022).
• pyspark.ml: Hosts machine learning algorithms, particularly regression models, streamlining model development within the PySpark ecosystem (Chhabra et al., 2023).
• pyspark.mllib: A comprehensive library, it encompasses basic statistics, classification, regression, clustering, and collaborative filtering functions, enhancing data analysis versatility (Belcastro et al., 2022).
• sklearn: Essential for model selection and evaluation, scikit-learn is a powerful Python package contributing to efficient machine learning model implementation and assessment (Chhabra et al., 2023).

Statistical Methods Used to Train the Models:
• Random Forest Regression: Executed via PySpark's 'RandomForestRegressor,' this ensemble learning technique enhances prediction accuracy through multiple decision trees, refining model robustness (Zhou, 2023).
• Linear Regression: Utilized the PySpark 'LinearRegression' module, enabling straightforward modeling of linear relationships between variables, crucial for predictive analysis (Xing et al., 2023).
• Generalized Linear Regression: Leveraged PySpark's 'GeneralizedLinearRegression' to extend traditional linear regression, accommodating diverse distribution families for better model adaptability (Singh, 2019).
• Statistical Correlation Analysis: Applied for scrutinizing variable relationships, this method examines connections between different features, providing insights crucial for model development and interpretation (Xing et al., 2023).
• Gradient-Boosted Trees Regression Model: Implemented through PySpark's 'GBTRegressor,' this model iteratively builds decision trees, correcting errors from prior trees, resulting in a powerful, accurate ensemble for predicting fish catch frequencies (Singh, 2019).
• Time Series Analysis: Integral to forecasting, time series analysis explores sequential data points. In this project, it aids in understanding and predicting trends in fish catch frequencies over the annual longitudinal survey period (Zhou, 2023).

Usefulness of the project
• Enhanced Operational Efficiency:
o The regression model of gradient-boosted trees provides high accuracy for forecasting the frequency of fish catches. This allows Alaskan fisheries to plan their operations better and match their resource allocation with the expected demand.
• Resource Management and Conservation:
o The regression model helps in managing the fisheries sustainably by giving accurate predictions. It helps to understand how variables like surface temperature, distance fished, and soak time affect the fish stocks and make informed decisions accordingly.
• Adaptability to External Factors:
o The model shows its adaptability by performing well even in unusual years affected by the COVID-19 pandemic. This adaptability is essential for the Alaskan fishing industry to cope with unexpected challenges and maintain its productivity and resilience.
