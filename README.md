# Zepto Product Inventory Analysis | SQL

PostgreSQL practice project on a Zepto product listing: **3,732 products across 14 categories**. Covers table design, exploration, cleaning and ten business questions on pricing, discounts, stock availability, category revenue and value for money. Every output in the document is the real result of running the query.

## Key findings
- **453 products (12.1%)** are out of stock; Biscuits have the highest stock-out rate at **28.6%**
- High-value items such as Patanjali Cow's Ghee (Rs 565) and MamyPoko diapers (Rs 399) are out of stock
- Fruits & Vegetables carry the highest average discount (**15.5%**); premium oils and ghee above Rs 500 sell at under 10% off
- Cooking Essentials and Munchies lead estimated revenue at about **Rs 3.37 lakh** each
- Staples such as salt and onions give the best value at about Rs 0.02 per gram
- Data quality: six category pairs hold identical product lists, and one zero-price product was removed

## What's covered
- Table setup with correct data types and CSV load
- Exploration: row counts, null checks, distinct categories, duplicate names
- Cleaning: paise-to-rupee conversion, removal of zero-price rows
- Business queries: top discounts, out-of-stock high-MRP items, category revenue, price-per-gram value

## Files
- `Zepto_SQL_Project_Report.pdf`
- `Zepto_SQL_Queries_and_Results.docx`

## Tools
PostgreSQL

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)
