# The King Crab Hack
## An analytical guide to the best bang for buck at the King Crab Shack using Mixed Integer Optimization and Google OrTools

<img src="images/kcs.png" width="1000" >

## Story
Furniture Co’s logistic department of is responsible for the last mile delivery (for more general information, see also [here](https://onfleet.com/blog/what-is-last-mile-delivery/)) from store to customers’ homes. 

## The Menu

| Seafood  | Price $/lb | 
| :------  | ---: | 
| crawfish	     |12.99 |
| mussels	     |12.99 |
| clams	     |12.99 |
| king crab    |	54.99|
| lobster tail (x1)	  |	26.99|
| lobster tail (x2)	  |	49.99|
| live lobster (x1)|	49.99|
| scallops	|	32.99|
| shrimp (whole)|16.99|
| shrimp (cleaned) |18.99|
| snow crab     |	35.99|
| dungeness crab|35.99|
| corn (x1)    |	0.75|
| potato (x1)	  |0.55|
| sausage (x1)	 |1.99|


|combo	|	included	|	price $/each	|
| :------  | ---: | ---: | 
|combo 1	|shrimp, mussels, crawfish/clams, corn, potato, sausage||41.99 |


## "Build Your Own Bag" or Combos? 


## Mission
Let us generate an assignment schedule for tomorrow by showing "who delivers which furniture". 

## Method
I implement a [Mix Integer Program (MIP)](https://en.wikipedia.org/wiki/Integer_programming) in a Python Jupyter notebook with [Gurobi](https://www.gurobi.com/) as the solver. Adding the following routine is necessary. 

```javascript
import numpy as np
import pandas as pd
from ortools.linear_solver import pywraplp
```
```javascript
A = pd.read_csv('input/combos.csv')
C = pd.read_csv('input/menu_byob.csv')
P = pd.read_csv('input/menu_combo.csv')
order = pd.read_csv('input/cust_order.csv')
D = order
```

```javascript

```

```javascript

```

```javascript

```

```javascript

```
## Result


## Reference



