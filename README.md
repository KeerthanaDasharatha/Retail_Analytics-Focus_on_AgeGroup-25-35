# Introduction:
This project explores customer purchasing patterns in a retail dataset, with a dedicated focus on the 25 to 35 age group. It aims to uncover trends, preferences, and insights that can assist in developing targeted marketing strategies, optimizing inventory, and improving customer engagement.

##  Focus on 25–35 Age Group:
All visualizations and data cleaning steps were filtered to retain only customers aged between 25 and 35, aligning the entire project with the target demographic.

## Dataset Overview:
The dataset has 1,500 rows and 12 columns.

##  Spreadsheet Column Names:
The dataset includes the following columns:

InvoiceID: A unique identifier for each transaction.

CustomerID: A unique ID for each customer making a purchase.

Gender: The gender of the customer (e.g., Male or Female).

Age: The age of the customer at the time of purchase.

ProductCategory: The category or type of product purchased (e.g., Electronics, Clothing, Grocery).

ProductID: A unique identifier for each product.

Quantity: The number of units of the product purchased.

PricePerUnit: The price of a single unit of the product.

PurchaseDate: The date when the transaction occurred.

StoreLocation: The physical location or city where the purchase was made.

PaymentMethod: The method used for payment (e.g., Cash, Credit Card, Digital Wallet).

TotalPrice: The total price paid for the quantity purchased.

## Libraries Used:
Python Standard Library : Built in python modules.

Pandas: For data loading, cleaning, and manipulation.

Numpy: Scientific computing with python

matplotlib: for creating basic charts.

seaborn: for advanced and visually appealing visualizations.

## Data Preparation:

Converted PurchaseDate to datetime.

Cleaned the data by removing null values.

Created TotalPrice as Quantity * PricePerUnit

The data is well-structured with no missing values after cleaning.

## Research Problem Statement:
How does age, gender, and payment method affect consumer spending behavior in a retail setting?
This project particularly focuses on customers aged 25–35 to identify trends in what they buy, how much they spend, and how they prefer to pay. These insights can help improve targeting, inventory management, and marketing strategies.

## Key Insights:
- Customers aged 25–35 are the biggest spenders.
  
- Digital payment methods are preferred by this age group.
  
- Certain product categories (e.g., electronics) dominate high-value purchases.
  
- Store locations and gender affect purchasing patterns.

## Conclusion:
The analysis reveals that customers aged 25–35 are the most active spenders, favoring categories like electronics and fashion. Digital payment methods are their preferred choice, and spending patterns show clear variation across genders and store locations. These insights can help retailers refine marketing, optimize inventory, and personalize customer engagement strategies.
