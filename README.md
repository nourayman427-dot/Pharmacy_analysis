# Pharmacy_analysis
This Project provides a comprehensive analysis of Pharmaceutical Sales, product profitability, inventory, expiration date.

📊 Project Objectives:

- Analyze total sales and profit performance.
- Calculate net sales, gross profit, and expected lost profit.
- Evaluate discount patterns across regions.
- Identify top profitable products.
- Assess inventory validity and expiration risk.
- Monitor quantity distribution across expiration buckets.
- Provide actionable insights to support business decisions.


| Column Name | Description |
|------------|-------------|
| sale_datetime | Date and time of each sales transaction |
| invoice_no | Unique invoice number |
| store_id | Store ID |
| store_name | Store name |
| region | Sales region |
| cashier | cashier name |
| customer_type | customer category |
| payment method | type of payment used |
|insurance Provider | name of insurance company |
| age | patient age |
|Gender | Patient Gender |
| brand_name | Product brand |
| Generic name | Pharamceitucal brand |
|manufacturer | Name of the product manufucter |
| expiry_date | Product expiration date |
| unit_price | Selling price per unit |
| cost_per_unit | Cost price per unit |
| quantity | Quantity sold |
| discount_amount | Discount value applied |
| sales_before_vat | Net sales before VAT |
| total_vat | VAT amount |
| sales_after_vat | Net sales after VAT |
| ExpirationDaysRisk | Bucket representing expiration risk category |

 🔧 **Data Preparation & Transformation (ETL Steps)**

- checked for null and duplicate records.
- Standardized date/time formats.
- Added calculated columns for expiration days.
- Created custom buckets for ExpirationDaysRisk.
- Calculated Net Sales, Gross Profit, and Net Profit.
- Calculated Expected Lost Profit for nearly expired inventory.
- Converted discount percentage into discount amount.
- Classified products into top performers.


📊 Dashboard Visuals Included
Sales Trend by Month
Top 5 Products by Profit and sales
Sales by Region
Valid Quantity by Expiration Buckets
Expected Lost Profit by Brand
Quantity Distribution by Region


🧠 Key Insights

Discount behavior varies significantly across regions and expiry risk levels.
Products nearing expiration represent a measurable financial risk.
Expected lost profit for nearly expired products is 6.83K
Certain brands are responsible for the highest portion of expected losses.


🚀 Conclusion & Next Steps

This dashboard enables better decision-making in sales, pricing, discount strategy, and inventory risk management.

👩‍💻 Author

Nour Ayman
Power BI | Data Analytics | Visualization
Profile : https://github.com/nourayman427-dot

Linkedin : linkedin.com/in/nour-ayman-220b11155/?skipRedirect=true

Gmail : nourayman427@gmail.com
