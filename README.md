# Linear Programming
## Supply Chain Optimization using Binary and Integer Constraints.

There are five customers whose demand has to be satisfied by building one or two warehouses.
The table below shows the location (X and Y coordinates) and demand (shipments per year) of each customer.
||Location||Demand||
|---|---|---|---|---|
|<b>Customer</b>|<b>X</b>|<b>Y</b>|Shipments/Year|Transport Cost/Mile|
|Customer 1|5|10|200|1.00|
|Customer 2|10|5|150|
|Customer 3|0|12|200|
|Customer 4|12|0|300|
|Customer 5|7|8|250|

The transportation cost is 1.00 GBP per mile.
Next table below contains parameters of the two warehouses (W1 and W2): their locations, cost to build (GBP), and capacity.
|Warehouse|X|Y|Cost to Build|Capacity|
|---|---|---|---|---|
|W1|3|4|50000|750|
|W2|100|101|30000|1500|

First consider the case when each customer can be served by only one warehouse.
Next allow shipments from both warehouses to the same customer.

<b>Objective:</b> Minimize the total cost.
