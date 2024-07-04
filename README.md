# ITSOLERA
## Project 1: Amazon Best Selling Books Analysis 
The Amazon Bestselling Books Analysis Model project aims to analyse the data of bestselling books on Amazon to uncover trends, patterns, and insights. By utilizing Python for data analysis, we seek to understand the factors contributing to a book's success, providing valuable information for authors, publishers, and marketers.
## Overview
1.	Data Collection: Gather data on bestselling books from Amazon.
2.	Data Cleaning and Preprocessing: Prepare the data for analysis by handling missing values, outliers, and ensuring consistency.
3.	Exploratory Data Analysis (EDA): Explore the dataset to understand the distribution, relationships, and key statistics.
4.	Visualization: Create visualizations to illustrate trends and patterns in the data using Seaborn and Matplotlib.
5.	Statistical Analysis: Perform statistical tests and construct models to identify factors influencing book sales.

## Installation
1. Clone the repository: sh git clone https://github.com/yourusername/ITSOlERA.git cd ITSOlERA
2. Install the required packages: sh pip install numpy pandas matplotlib seaborn scikit-learn

## Analysis
### Visualization 
1. Bar charts and pie charts illustrated the distribution of genres and authors.
2. Included scatter plot shows the alignment between Price and Rating.
3. Line graphs showed trends over time, such as changes in average ratings.
4. 3d projection of scatter plot to visualized relationships, such as price, rating and sales rank

### Statistical Analysis
•	Hypothesis testing confirmed the significance of various factor
T-statistic: -0.58 (approximately), suggesting that the means of the two groups (Fiction and Non-Fiction) are very close to each other. P-value: 0.55, which is much higher than the typical significance level (e.g., 0.05). 
#### Interpretation: Fail to Reject the Null Hypothesis: This means there is no statistically significant difference between the average sales ranks of Fiction and Non-Fiction genres in your dataset. The high P-value suggests that any observed difference in means is likely due to random chance. You can conclude that, based on this analysis, the sales ranks for the Fiction and Non-Fiction genres are similar.
•	Regression analysis identified key predictors of sales rank e.g.: Price, Number of Reviews, Ratings, Genre.

•	Clustering grouped books with similar characteristics, revealing [specific insights, e.g., common traits among top-selling books].

## Conclusion
This project provides valuable insights into the factors contributing to a book's success on Amazon. By leveraging Python for data analysis, we have uncovered patterns and trends that can inform authors, publishers, and marketers in their strategies. The findings from this analysis offer actionable recommendations for improving book sales and achieving greater success in the competitive book market.


