# Project Requirements — Excel Sales Analytics Mini-Project

## 1. Project Overview

This project is an instructor-assigned Excel mini-project focused on analysing customer orders, sales performance, product demand, discounts and delivery efficiency.

The objective is to use Excel formulas, calculated columns, PivotTables, charts and a dashboard to transform order-level data into meaningful business information.

## 2. Customer KPIs

Calculate the following customer metrics:

- Total unique customers
- Customer with the highest order amount
- Average customer age

## 3. Order and Delivery KPIs

Calculate:

- Total orders placed
- Average number of days taken to deliver orders
- Total orders with zero delivery charge

## 4. Product KPIs

Calculate:

- Total unique products
- Most frequently ordered product
- Product generating the highest sales after discount and delivery charges are adjusted

## 5. Sales KPIs

Calculate:

- Total amount generated before discounts
- Total discount offered
- Total amount after discount
- Total amount after discount and delivery charges

## 6. Required Calculated Columns

Create the following columns in the dataset:

### Days to Deliver
Calculate the number of days between the order date and delivery date.

### Amount
Calculate the order amount using price and quantity.

**Calculation:** Price × Quantity

### Discount_Percent
Derive the discount percentage from the coupon code:

| Coupon code | Discount percentage |
|---|---:|
| FLAT8 | 8% |
| FLAT10 | 10% |
| FLAT15 | 15% |
| FLAT20 | 20% |
| DEL0 | 0% discount and zero delivery charge |

### Discounted Amount
Calculate the amount remaining after applying the applicable discount.

### Amount_with_Delivery_Charge
Add the applicable delivery charge to the discounted amount. When the coupon code is `DEL0`, the delivery charge must be zero.

### Full_Name
Combine the customer's first name and last name.

### Delivery_Status
Classify deliveries as `Late`, `Intime`, or `BeforeTime`, based on the difference between the order date and delivery date, following the assignment's intended delivery-timing rule.

## 7. Visualisation Requirements

Create PivotTable-based visualisations wherever appropriate:

1. **Top 10 Customers:** Bar chart showing the highest total sales after discount and delivery charges.
2. **Top 7 Products:** Donut chart showing the count of the most frequently ordered products and their percentages.
3. **Orders by City:** Funnel chart showing the total number of orders for each city.
4. **Sales by City:** Bar chart showing total amounts after discounts and delivery charges.
5. **Coupon Usage:** Pie chart showing the count of each discount coupon used.
6. **Monthly Sales by Gender:** PivotTable and clustered bar chart showing order month, gender and total amount after discounts and delivery charges.

## 8. Dashboard Requirements

Create an interactive and visually appealing dashboard containing the required KPIs and charts.

The dashboard should present the main findings clearly and help users explore customer, product, sales, coupon and delivery performance.

## 9. Expected Deliverables

- Completed Excel workbook
- Calculated columns and KPI summaries
- Required PivotTables and charts
- Consolidated dashboard
- Documentation of project requirements

## 10. Project Scope

This is an educational Excel analytics project. The results should be interpreted in the context of the supplied dataset and the business rules specified in the assignment.


