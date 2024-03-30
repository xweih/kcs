# The King Crab Hack
## An analytical guide to the best bang for buck at the King Crab Shack using Mixed Integer Optimization and Google OrTools

<img src="images/kcs.png" width="1000" >

## Story
As a foodie, I have soft spot for seafood and Vietnamese food. My favorite restuarnt to get both in Milwaukee is this place called King Crab Shack. They serve not only authentic Vietnamese dishes, but also cajun style seafood boil with a twist of Vietnamese. 

Their menu can be found [here](https://thekingcrabshack27th.com/menu).  

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


|Combos	|	Included	|	Price $/each	|
| :------  | ---: | ---: | 
|combo 1	|shrimp, mussels, crawfish/clams	|	41.99 |
|combo 2	|snow crab, mussels/crawfish	|	45.99 |
|combo 3	|snow crab, 2x lobster tails	|	82.99 |
|combo 4	|snow crab, shrimp, mussels	|	59.99 |
|combo 5	|snow crab, crawfish, clams	|	58.99 |
|combo 6	|2x lobster tails, shrimp, mussels	|	73.99 |
|Dungenese combo 	|Dungenese crab, shrimp	|	54.99 |
|King crab combo	|King crab, shrimp	|	72.99 |
|Live lobster combo	|1 x live lobster, mussels	|	62.99 |
|combo special 1	|snow crab (1/2), 1x lobster tail, shrimp (1/2) 	|	49.99 |
|combo special 2	|King crab (1/2), shrimp (1/2), crawfish/mussels (1/2)	|	39.99 |


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



