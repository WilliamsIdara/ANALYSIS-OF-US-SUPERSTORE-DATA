#ANALYSIS-OF-US-SUPERSTORE-DATA

INTRODUCTION
To operate successfully in business, business needs analysis of their data. These analysis offers insightful information about how their organization are doing in terms of sales and helps to guide important business choices. They can find areas for improvement, assess the success of their sales tactics and reach well informed judgement by evaluating sales data.

Superstore is a business in the United States which deals in the sales of furniture, office supplies and technology product and their customers are consumer, corporate, home offices and small business. The dataset contains sales, profit, geographical information, customer information, etc. The aim of this analysis is to uncover significant insights that can be used by Superstore to assess their performances, pinpoint areas for development and make wise decisions that promote expansion and profitability.

BASIS

The dataset used in this project was obtained from Kaggle.com named [SuperstoreUS](Kaggle.com/datasets/amrboghdady74/superstoreus). The dataset was collated on a spreadsheet (Microsoft excel) with column heads which includes.
Order Priority: High, Low, Critical or Not specified.

Customer ID: Unique ID of each customer

Ship Mode: Express Air, Delivery truck, Regular Air

Customer Segment: Corporate, Home Office or Small business

Product Category: Office Supplies, Furniture or Technology

Order ID: Unique ID of the orders

Ship Date: Delivery date

Order Date: Date order was made.

Region: West, Central or East

Product Container: Wrap box, Jumbo drum, small pack, medium box or Jumbo box.

Postal Code: Location

QUESTION/INSIGHT

· Which city had most profit?

· Which city had least profit?

· Which city had most sales?

· Which city had least sales?

· Which month had the highest and least profit?

· Which month had the highest and least sales?

· Which Customer Segment is most profitable?

· Which Customer Segment had the highest number of sales?

· Which region had the most sales?

· Which Category and sub-category has the most and least number of sales?

PROJECT STRATEGY

Before analyzing dataset, it is important to ensure that the data is properly cleaned, as this will ensure accuracy and credibility of the insights generated from the data. I uploaded the data set to Power Bi and carried out cleaning and preparation on Power Query. Under this step, I considered data types/format, duplicates and null values. The following cleaning was carried out on Power Query.

· I changed the data type on the Postal code column from number to text. This is because postal code is more of an address than numeric.

· I transformed order date as well as standardize its format/data type to date using split column by delimiter.

· I made duplicates from the fact table with titles, Customer, Product and Location. Duplicates were removed from each column (Customer, Product and Location), null columns were replaced with values.

· Three new columns (Customer Key, Product Key and Location Key) were added to the SuperStoreUS field to enable counting and give identity to Customer, Product and Location table.

NB: Columns were appropriately selected and unneeded columns hidden.

My model procedure was to create a relationship between Superstore field and the Customer, Product and Location field.

VISUALIZATION

The Visualization of the Superstore sales data was able to give reasonable insights such as; City with the most and least profit, city with the most and least sales, month with the highest and least sales, month with the highest and least profit, most profitable customer segment, customer segment with the highest number of sales, -most profitable region, category and sub-category with the most and least number of sales, Total revenue and profit, Total customers and profit percentage.

[Link to Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjQwN2E0MDgtOThkOC00MzU4LThlYzQtY2YwYTU1MjQzN2M3IiwidCI6ImQ2N2NmOWE0LTk5MTgtNGVhNC04YWE0LWJhYzVjMTQ2YTM4ZCJ9)
