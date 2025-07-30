# 🛍️ Customer Spending Analysis (2011)

This Python project analyzes customer transaction data from an Excel file (Data.xlsx) and calculates key statistics about spending in selected countries.

---

## 🎯 Objective

We calculate the following statistics per country:

- Median of total spending per customer
- Mean of total spending per customer
- Mode of total spending per customer

---

## 📂 Dataset Info

The data comes from a retail transaction log with ~541,910 rows.  
Each row contains:

- InvoiceNo: Invoice ID  
- StockCode: Product code  
- Description: Product description  
- Quantity: Number of items bought  
- UnitPrice: Price per item  
- InvoiceDate: Date of purchase  
- CustomerID: Unique customer ID  
- Country: Customer's country  

---

## 🔎 Filters Applied

Only include data that meets all the following:

1. Transaction year is 2011
2. Customer’s total purchase is greater than 40
3. Country is in the following list:

Australia, Canada, Brazil, Denmark, Finland, France, Greece, Germany, Italy, USA, Norway, Saudi Arabia, Belgium

---

## 🧾 Final Output

The final output is a table that shows for each country:

| Country        | Median  | Mean    | Mode   |
|----------------|---------|---------|--------|
| France         | 235.20  | 237.10  | 205.70 |
| Germany        | 180.00  | 192.40  | 180.00 |
| ...            | ...     | ...     | ...    |

This table summarizes customer spending behavior across countries.

---

## ▶️ How to Run

1. Make sure Python is installed.
2. Install the required libraries:
```bash
pip install pandas numpy openpyxl
```
3. Put your Excel file (Data.xlsx) in the same folder as the script.
4. Run the script
