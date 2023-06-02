
## Project Overview

This project focuses on XYZ Real Estate Agency, situated in a vibrant northwestern county, and aims to analyze key factors influencing house prices in the area. By developing a robust multiple linear regression model, the agency can determine optimal pricing strategies and enhance their annual sales. The project utilizes data-driven strategies and analytical insights to reimagine real estate and transcend conventional boundaries.

### Business Problem

XYZ Real Estate Agency needs assistance in identifying the crucial factors that impact house prices. The agency seeks to leverage this information to guide their pricing strategies and increase their annual sales. The project's main objective is to develop a reliable model that accurately predicts housing prices and provides valuable insights to enhance decision-making.

### Project Objectives

- Identify the significant features that influence house prices in the northwestern county.
- Develop an optimal pricing strategy using a robust multiple linear regression model.
- Identify overpriced or underpriced houses by comparing predicted and actual prices.
- Improve the agency's annual revenue by leveraging analytical insights and the developed pricing strategy.

### Data Description Report

The dataset used in this project consists of 21 columns and 21,597 rows, encompassing various data types such as float, integer, and object. Some columns contain missing values, which were handled by dropping the corresponding rows. Data cleaning procedures included converting data types and creating a subset of features for analysis. Exploratory data analysis techniques, including univariate and bivariate analysis, were applied to gain insights into the dataset's characteristics.

### Exploratory Data Analysis

Univariate analysis involved examining the distribution and characteristics of individual variables, while bivariate analysis focused on exploring relationships between variables. Scatter plots and bar plots were utilized to visualize the correlation between numerical and categorical variables with the house prices. Multivariate analysis incorporated a heatmap to display the correlation between all columns in the dataset.

### Model Development

Four models were developed during the project. The baseline model, utilizing a simple linear regression, established the initial understanding of the relationship between the square footage of living space and house prices. From the simple linear model, it was observed the model wasn't the best for this analysis. The model's R2 value was extreemly low, indicating that there are other numerous factors in housing that affect the house prices. These results showed that another iteration was needed. In the second model OneHot Encoding was introduced to convert the categorical variables to binary representation which is suitable for machine learning algorithms. The second model certainly improved from the baseline model. The R2 was at 80.8%; The F-statistic of 692.2 with a probability (p-value) of 0.00 suggests that the overall model is statistically significant, meaning that at least one of the independent variables has a significant effect on the dependent variable. To further improve the model, a third iteration was needed, In this model, Log Transformation was introduced to reduce skewness. The results from this iteration reduced skewness while simultaniously increasing the R2 making the model highly significant. The final model, a multiple linear regression, incorporated additional features to improve the predictive power. Evaluation metrics such as R-squared and F-statistic were used to assess the model's performance and significance. In this model, insignificant variables were dropped to achieve the highest prediction power of the models. The results gotten from this model's summary displayed the highest R2 value, and the best fit of residuals to a normal distribution. 

### Conclusion

The multiple linear regression model successfully identified key factors influencing house prices in the northwestern county, achieving an adjusted R-squared value of 0.835. Features such as square footage, waterfront location, property grade, and specific zip codes were found to significantly impact house prices. The model's findings and the developed pricing strategy can assist XYZ Real Estate Agency in making informed pricing decisions and maximizing sales potential.

### Recommendation

Based on the analysis conducted, the following recommendations are proposed:

1. Focus on key features: Pay close attention to features such as square footage, waterfront location, property grade, and specific zip codes, as they significantly influence house prices in the area.

2. Optimize pricing strategy: Utilize the developed multiple linear regression model to create an optimal pricing strategy. Consider the coefficients obtained from the model to set competitive and attractive prices for listed properties.

3. Identify overpriced and underpriced houses: Regularly compare predicted prices from the model with actual prices to identify overpriced or underpriced properties. Make necessary adjustments to pricing to maximize sales potential.

4. Leverage analytical insights: Incorporate the analytical insights derived from this research into decision-making processes to gain a competitive advantage, attract more buyers, and increase overall sales volume.

### Next Steps

To further enhance the project, the following steps are recommended:

1. Incorporate temporal dynamics: Analyze how the housing market changes over time by considering seasonal trends, price fluctuations, and long-term market dynamics using time series analysis techniques.

2. Collaborate with domain experts: Engage in discussions

 and collaborations with real estate experts or domain specialists to gain deeper insights into the market and validate the analysis conducted.

3. Refine the model: Explore other regression techniques, address issues such as multicollinearity, overfitting, and underfitting to improve the accuracy and predictive power of the model.

4. Stay updated and iterate: Continuously update the model with new data and monitor industry trends to ensure its accuracy and relevance in the evolving real estate market.
