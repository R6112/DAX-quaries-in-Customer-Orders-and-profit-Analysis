 **Customer Orders & Profit Analysis**

**Overview**
This repository contains a Power BI dashboard that visualizes and analyzes customer orders and profit-related data. It uses two tables: Customer and Orders, with DAX queries to perform key calculations and display insights.

**Key Visualizations**

**Stacked Column Chart (Orders by Month):** Displays the number of orders placed each month.
**Stacked Column Chart (Orders by Day):** Visualizes the number of orders placed each day.

**Cards:**

**Total Orders:**100 orders in total.
**Order Count:** 100 orders (based on filters).
**Unique Order Count:** 100 unique orders.
**Profit & Cost:** Total profit and cost is 21,575.
**Customer Orders Table:** Shows customer names and their total order counts.
**Total Sum of Order:2,858 total order units.

**DAX Calculations**
Key DAX queries used for calculations:

OrderCount = COUNTROWS('Orders')

UniqueOrderCount = DISTINCTCOUNT('Orders'[OrderID])

TotalProfitCost = SUM('Orders'[Profit]) + SUM('Orders'[Cost])

TotalSumOrders= SUM('Orders'[OrderAmount])


![Screenshot 2025-01-23 143921](https://github.com/user-attachments/assets/c137e719-8e94-4c90-a5a2-e9307bfd6b30)
![Screenshot 2025-01-23 142517](https://github.com/user-attachments/assets/d53ef1fe-765d-49ed-b56c-59e07c5a5205)
![Screenshot 2025-01-23 142614](https://github.com/user-attachments/assets/18b5da7e-461c-40f7-ae19-c156283fd402)
![Screenshot 2025-01-23 142543](https://github.com/user-attachments/assets/78e42af6-1213-49ce-9a60-556a7c539fff)


