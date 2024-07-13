# Coffee Chain Project

## Problem Statement 
-This data can be used to identify the sales of Coffee at a coffee chain throughout the United States. This prediction model can give insight to cofee chains that are interested in the factors that may affect the sales of their coffee as well as knowing what are the best selling products and the least selling products; how much is spent in manufacturing those products and the profit made. 
-The data looks at a coffee chain through out the United Sates in the central, west, south and east regions. The columns consist of Product ID, Product Type, State, Market, Profit, Cogs, Product, Type, Market Size, Budget Sales, Budget Profit, Sales, Total Expenses and Date. These are the factors that contribute to the sale of the products. 

## Modeling Process
-I beleive my model will generalize to new data because it performed well to that it has not seen. I demonstrated feature engineering by selecting features relevant to Sale. I also used visulizations such as a heat map to gain insight on the fatures with significant correlation to the target and improved the model. The baseline score was 96%. I created a linear regression model using 'Product Id', 'Product Type Num', 'Product Category', 'Type of Coffee', 'Size of Market', 'Market Location', 'Budget Sales', 'Budget Profit', 'Cogs'and 'States' as features.

## Data Dictionary
|Product ID    | Product Number                                                                                     | 
|Product Type  | Type of Product                                                                                    |
|Product       | Products Offered                                                                                   | 
|Type          | Type of Coffee                                                                                     |
|Market Size   | Size of the Market                                                                                 |
|Market        | Location of the Market                                                                             |
|State         | Store Location                                                                                     |
|Budget Sales  | Estimated Revenue                                                                                  |
|Budget Profit | Expected Income and Expenses                                                                       |
|Cogs          | Cost of Goods Sold. The direct costs attributable to the production of the goods sold by a company.|  
|Profit        | Financial Gain                                                                                     |                                                                                   
|Sales         |                                                                                                    |
|Total Expenses| The sum of all costs                                                                               |
|Date          | Date of purchase                                                                                   |

## Executive Summary

### Data Cleaning Steps
I first imprted all the tools I needed such as pandas, matplotlib, seaborn, etc. The shape of the dataset consist of 4,248 rows and 14 columns. I then nrenamed Type to Coffee Type for clarity and Date to Date Time because  the date column also as the time. For products I replaced teh name of each product with the a corresponding number; as well as changing the column from product to product category. I did the same replacing the names with numbers and chnaging the column names for the following product type to product type num, coffee type to type of coffee, market size to size of market, market to market location and state to states.

### Key Visualizations
Include key visualizations that highlight important aspects of the data. Use graphs, charts or any other visuals representaion to make your points. 

#### Visualization 1: ['Distribution of Product Types']
[The most common product type is Espresso having a count of almost 1200. Herbal Tea and Coffee have similiar counts. Tea sis the least common with a count of almost 1000.]

[Coffee Chain Project](Visualizations/countplot1.png)

### Visualization 2: ['Distribution of Markets']
[The small market is most common in the west out of the four markets. The major market is most common in the central market compared to the other markets.]

[Coffee Chain Project](Visualizations





