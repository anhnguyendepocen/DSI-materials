# Problem Statement

Property prices are often subject to fluctuations due to a plethora of reasons. Understanding the underlying contributions of various factors that shape property pricing would be highly insightful. **Therefore, the aim of this project is to predict house prices in using regression models.** Specifically, the housing data of Ames,Iowa would be used for the scope of the project.

# Executive Summary
The following is the executive summary of the project:

**1. Problem statement**

This section covers the problem statement related introductions of the project

**2. Data Cleaning and Exploratory Data Analysis**

This section describes the steps involved in the exploration and cleaning of the available dataset

**3. Test set data cleaning and imputation**

This section describes the steps taken to clean and impute data on the test set

**4. Feature selection and modelling**

This section covers the feature selection alongside the modelling process

**5. Re-training the best model**

This section covers the steps taken to re-train the chosen model

**6. Submission for Kaggle competition**

This section covers the steps taken to submit the necessary files for the Kaggle competition

**7. Conclusion, findings and recommendation**

This section wraps up the conclusion, findings and recommendation of the project


# Data Dictionary

The data for this project is taken from http://jse.amstat.org/v19n3/decock/DataDocumentation.txt, which contains the dataset of housing prices in Ames, Iowa from 2006 to 2010. As such, the data dictionary provides a thorough breakdown of the variables involved.

# Conclusion/Recommendation

1. One key finding and learning point is the huge difference in the R^2 score when the outliers were removed. There was an improve of over 0.1 in each of the models tested (linear regression, lasso, ridge), from the 0.7 range to the current range (not shown in this notebook). This goes to show the strong influence that an outlier can have on a predictive model, and it would be necessary to pay close attention to such outliers. In this particular case, they were removed. However, there may be models where the outliers are very much necessary to the validity of the model.

2. Another finding that we have is that the model does reveal important features that are similar to what a layman would expect: space-related variables were often the driving force behind sale price (intuitively: the larger the house and land, the more is required for it). This model hence confirms and puts a quantitative spin on certain beliefs that are held regarding the factors influencing property pricing. (which is unsurprising)

3. At its current stage, this model can be used as a very rough estimator of property pricing in Ames. Specifically, should the model be deployed and brought to the market, property agents would be able to engage the model by varying variables on the interface of a handheld device, buyers and sellers would possibly be able to assess the price of their existing house on a rough basis without any valuation experts.

4. However, as the model is still in an infancy stage, it would do better to have data collected over a longer timeframe. This would allow more instances of data to be fed into the model, generating better results. Specifically, the current model seems to show greater variance in the higher sale price region, and the feeding of more such data would ensure a more accurate model in that regard.

5. In terms of the creation of a better model, the method of data collection should also be revised to include a more quantitative response. One of the subjective aspect of this model is the encoding of qualitative responses into quantitative ones, and if the very design of the survey used to evaluate the houses takes this into consideration, it would certainly add weight to the accuracy of the response, and therefore, the model.
