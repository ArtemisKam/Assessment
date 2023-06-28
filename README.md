# Assessment

Plan I - Query 1: This table represents the basket, frequency of ordering and percentage of users with more than 3 orders, both for “Breakfast” 
orders and for total efood orders. As we can see from the table, for the 5 cities with the most Breakfast Orders, it seems that their “Breakfast” 
basket is much smaller in value than their basket of efood orders. This indicates that although these are the cities with the most 
“Breakfast” orders, the amount of order value is pretty smaller than that of efood orders in general, as well as the percentage of users
that make more than 3 "Breakfast" orders.

Plan II: The code firstly selects the user_id and counts the order_ids, to calculate the frequency of orders and then adds all the different 
amount values to calculate the total order value. The next step is the use of the quantiles methodology, in order to create the user segments. 
So, 5 quantiles are created and according to different values of the frequency and the monetary value, they are characterized as "High Value", "Loyal", "Low Value" and "Promising". For example, if monetary and frequency are in the 4th or 5th quantile they are considered as "High Value".
