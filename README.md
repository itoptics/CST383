# CST 383-30 Summer 2023 - IT Optics Final Project Report
### Christian Rodriguez, Emmanuel Salcedo, Ranjita Summan, Crystian Chavez
### Mehmet Ergezer [@profmemo] ((https://github.com/profmemo))
### 16 June 2023
## 
### Introduction 
The project was undertaken to build a system that predicts the cost of a home based on features such as square footage, number of bedrooms, and number of bathrooms. The goal was to provide a tool that can help individuals and real estate professionals estimate the value of a home in the USA. The research question was: Can we predict the cost of a home in the USA based on its square footage, number of bedrooms, and number of bathrooms? The purpose of the research was to develop a predictive model that can provide insights into the relationship between these features and the price of a home. The source of the dataset used in this project is the "USA Real Estate Dataset" from Kaggle. The dataset contains information about real estate properties in the USA, including features such as the status of the property, number of bedrooms and bathrooms, square footage, city, state, zip code, previous sold date, and price. The data consists of 407,890 entries with 10 columns, including both numerical and categorical data. The data preprocessing steps included handling missing values and removing rows with missing data in important columns such as the number of bedrooms, number of bathrooms, and square footage. Outliers were also identified and removed to improve the accuracy of the analysis and visualization.

### Methods 
The materials and tools used in this project include Python programming language, Jupyter Notebook, and various libraries such as numpy, pandas, matplotlib, seaborn, and scikit-learn. These tools were used to perform data analysis, visualization, and model building for answering the research question.

### Results
The study found that there is a correlation between the number of bedrooms, number of bathrooms, and square footage of a home with its price. However, the predictive model based on linear regression showed limited accuracy in predicting home prices solely based on these features. The coefficient of determination (r-squared value) was found to be quite low, indicating that the model explains only a small portion of the variability in home prices. Visualizations, such as scatter plots, were used to explore the relationships between variables and identify outliers. Count plots were used to visualize the number of homes for sale per state. The scatter plot with the regression line demonstrated the relationship between the number of bedrooms and home prices.

### Discussion
The answer implies that while the number of bedrooms, number of bathrooms, and square footage have some influence on the price of a home, they are not the sole determinants. Other factors, such as location, amenities, market conditions, and additional features, might play significant roles in determining home prices. This finding aligns with previous research that has identified multiple factors affecting home prices. Future research can focus on incorporating additional features and factors into the predictive models to improve accuracy. Additionally, exploring more advanced modeling techniques, such as ensemble methods or non-linear regression, may help capture complex relationships and improve predictions.

### Summary
When building out a model to predict pricing targets, it is important to use more than two predictors when training your algorithm. In our case, though the number of bedrooms and baths in a home does affect pricing, we found there is a wide range in pricing due to the fact of other factors coming into play. By increasing the predictors, careful data cleaning, and preprocessing there is potential to improve our models and provide valuable information to future home buyers. With the current issue, we face today of low housing inventory and high price homes, being able to find a deal on a home is now more important than ever.
