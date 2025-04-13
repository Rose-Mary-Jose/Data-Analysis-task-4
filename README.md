-- Column to estimate profit
Estimated_Profit = 'Train'[Item_Outlet_Sales] - ('Train'[Item_MRP] * 0.7)

the a bove is the code for the column Estimated_Profit



-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
KPIs:

- Total Sales: Sum of `Item_Outlet_Sales`.
- Estimated Profit: Calculated as `Item_Outlet_Sales - (Item_MRP * 0.7)`.
- Average Sales per Item: Average of `Item_Outlet_Sales`.
