# Nigeria-Economy-Growth-1990-2023--Excel
This project is about Analyzing an economic dataset, I'll be focusing on the Nigerian Economic Dataset from 1990 to 2023. Nigeria, one of Africa's largest countries, boasts a substantial economy, having held the highest GDP on the continent at one point.  This analysis holds personal significance for me, given its connection to my home country.

### About
Nigeria boasts the largest economy in Africa, as measured by Gross Domestic Product (GDP), which reflects the total value of goods and services produced within the country. This key indicator is pivotal in assessing Nigeria's economic progress.

In this data analysis, we aim to forecast Nigeria's future growth trajectory and explore potential variables that could impede its development. Additionally, we'll investigate the influence of leadership on the nation's economic expansion.

I believe this dataset warrants more than just basic descriptive statistics and summarization with measures like mean, median, and mode. There's significant potential for deeper analysis and exploration within this dataset.

This dataset pertains to economics, and a superficial analysis using basic EDA and descriptive statistics may not provide a comprehensive understanding. Although I initially conducted some basic descriptive statistics to identify preliminary patterns, it's evident that deeper analysis is required.

###### I'll approach it from an economic and econometric perspective.
Econometrics is a branch of economics that utilizes statistical techniques to model economic situations. Therefore, my analysis will not only focus on economic principles but will also incorporate various statistical techniques.

### About the Dataset
The dataset consists of 10 Columns and 35 records, See the source of the dataset [Nigeria Economy Growth 1990-2023](https://www.kaggle.com/datasets/ogbuzurukelechi/nigeria-economy-growth-1990-2023/data)

#### Purposes Of The Project
> The first step in this analysis is to understand the aims and objectives of the dataset. 
> The provided dataset revolves around Nigeria's economy, highlighting the significance of Gross Domestic Product (GDP) as a key indicator of economic development. 
> The dataset aims to assess Nigeria's growth potential and identify factors that could potentially hinder its development. Additionally, we seek to explore the role of leadership in      driving the country's expansion. 
> In summary, the analysis will focus on evaluating Nigeria's growth trajectory from 1990 to 2023, examining contributing factors and potential obstacles to its development.

When I open the dataset, I notice that it encompasses the entire Nigerian economy from 1990 to 2023. Additionally, there are four extra sheets, each corresponding to a different president. These presidents include Obasanjo, who served from 1999 to 2007, followed by Yar'Adua, Goodluck Jonathan, and Buhari.

It's crucial to focus on key indicators that determine a country's growth, including the inflation rate, unemployment rate, and government debt. In a growing or developing country, the unemployment rate should ideally decrease over time, along with government debt, while maintaining a stable inflation rate.

This dataset is rich in economic data, featuring a time series from 1990 to 2023. Given the temporal nature of the data, conducting a comprehensive time series analysis, particularly time series forecasting, is essential. Time series forecasting allows us to predict future values of key indicators such as inflation rate, unemployment rate, government debt, and GDP at constant basic prices. While I won't delve deeply into time series forecasting in this analysis due to its complexity and time-consuming nature, I will perform basic time series analysis to uncover patterns and trends.

Upon reviewing the dataset, I encountered variables such as agriculture, industry, and services. Although the specific definitions were not readily available, I inferred that these variables represent average values over time.

### In analyzing the dataset, I will employ Some statistical techniques:

> Descriptive statistics and exploratory data analysis: This involves summarizing, describing, and exploring the dataset to gain insights into its characteristics and distributions.

> Time series analysis and forecasting: While I won't focus extensively on time series forecasting in this analysis, I will conduct basic time series analysis to identify patterns and trends over time.

> Another crucial aspect of this analysis is to build a regression model. Given the econometric nature of the dataset, constructing an econometric model is essential for predicting variables such as inflation rate, unemployment rate, government debt, or other key indicators. Regression analysis will enable us to understand the relationships between different variables and make predictions based on these relationships.

#### Let's start by conducting descriptive statistics.
These are the summary statistics for each variable in our dataset

![Descriptive Statistics for each variable](https://github.com/Jamaderibigbe/Nigeria-Economy-Growth-1990-2023--Excel/blob/main/Descriptive%201.PNG) 
--
![](https://github.com/Jamaderibigbe/Nigeria-Economy-Growth-1990-2023--Excel/blob/main/Descriptive%202.PNG)

The next step is to visualize and explore each variable over the years. We aim to understand how inflation rate, unemployment, government debt, and other numerical variables have changed over time. To achieve this, we will insert a pivot table, allowing us to analyze the data and visualize the trends more effectively. Let's proceed by inserting a pivot table.

