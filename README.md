# Food Delivery Profitability Analysis (Excel)

An Excel analysis of 100,000 food delivery orders (Jan 2025 – Aug 2026) to find where the business makes and loses money.

## Business questions
1. Which food types make the most profit per order?
2. Do promo codes help or hurt profit?
3. Does weather change delivery time and customer ratings?

## Key numbers (Delivered orders only)
| Metric | Value |
|---|---|
| Delivered orders | 91,976 (92% of all orders) |
| Revenue | ₹4.73 crore |
| Profit | ₹93.7 lakh |
| Profit per order | ₹101.84 |

## Findings
- **Promos cost profit:** promo orders earn about ₹32 less per order than orders with no promo. About 4% of promo orders lose money, against about 1% without a promo.
- **Weak food types:** Burgers, Momos and South Indian earn only ₹46–51 profit per order, against ₹150 for Chicken. With a promo, Burgers, Momos and South Indian earn only about ₹29–38 per order.
- **Rain slows delivery:** about 45 minutes in rain, against about 37 on clear days. Ratings stay the same (about 4.36).
- **Limit:** promo orders were already lower-value, so this shows a link, not proof that promos cause lower profit.

## Recommendations
1. Pause promos on Burgers, Momos and South Indian.
2. Test a smaller discount on other low-profit food types.
3. Plan extra delivery time on rainy days.

## Data cleaning
| Problem | What I did |
|---|---|
| Cancelled and refunded orders carry money values (8%) | Used Delivered orders only for all totals |
| Order dates were a mix of text and wrongly swapped day/month | Built a clean date column (Order_Date_Clean) |
| Customer ID has many different names | Did not do customer-level analysis |
| New_Customer flag looks unreliable | Did not use it |
| Ratings missing on 18% of delivered orders | Ignored blanks in averages |

## Tools and skills
Excel: PivotTables, PivotCharts, COUNTIFS, SUMIFS, IF, DATE formulas, data cleaning and checking.

## Screenshots
<img width="1470" height="743" alt="excel" src="https://github.com/user-attachments/assets/e525abfa-2bd5-4127-8124-1cc2b3705263" />



## Files
- Excel workbook (Data, Pivot, Summary, Data_Note sheets): https://1drv.ms/x/c/744b6700ad99c87a/IQAykZjlbSrgQYBBEulv_BSTAVYei_0uTR787y5eMMrgh0I?e=MpFkxX
- Dataset: https://1drv.ms/x/c/744b6700ad99c87a/IQDCFMczpUKZSrgh1FINcLkPAbhtEnTBHMmxJl77NY220UA?e=xbetsQ This is a practice dataset, so the findings are for learning and do not describe the real Uber Eats business.

## Author
Jesal Chaudhari – https://www.linkedin.com/in/jesal-chaudhari-b560b139a/
