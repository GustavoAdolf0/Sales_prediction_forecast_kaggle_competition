# Kaggle Competition: Sales Prediction Forecast

This Kaggle competition revolves around a complex time-series dataset, featuring daily sales data provided by one of the largest Russian software firms, 1C Company. The primary objective is to predict the total sales for each product and store in the upcoming month.

To access the kernel for this competition, visit the Kaggle website: [Sales Forecast - Univariate and Multivariate LSTM](https://www.kaggle.com/charles75/sales-forecast-univariate-and-multivariate-lstm)

## Data Overview

### Data Description
The dataset comprises daily historical sales data, with the task of forecasting the total quantity of products sold in each shop for the test set. The dynamic nature of the list of shops and products, which slightly changes each month, adds complexity to the challenge. Building a robust model capable of adapting to such variations is a key aspect of this competition.

### File Descriptions
1. **sales_train.csv:** The training set, encompassing daily historical data from January 2013 to October 2015.
2. **test.csv:** The test set, where the goal is to forecast sales for these shops and products in November 2015.
3. **sample_submission.csv:** A sample submission file in the correct format.
4. **items.csv:** Supplemental information about the items/products.
5. **item_categories.csv:** Supplemental information about the item categories.
6. **shops.csv:** Supplemental information about the shops.

### Data Fields
- **ID:** An identifier representing a (Shop, Item) tuple within the test set.
- **shop_id:** A unique identifier for a shop.
- **item_id:** A unique identifier for a product.
- **item_category_id:** A unique identifier for the item category.
- **item_cnt_day:** The number of products sold, with predictions focusing on a monthly quantity of this measure.
- **item_price:** The current price of an item.
- **date:** The date in the format dd/mm/yyyy.
- **date_block_num:** A consecutive month number used for convenience, where January 2013 is 0, February 2013 is 1, and so forth, up to October 2015 being 33.
- **item_name:** The name of the item.
- **shop_name:** The name of the shop.
- **item_category_name:** The name of the item category.

Engage in this competition to showcase your skills in time-series forecasting and contribute to predicting sales in a dynamic retail environment.
