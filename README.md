# The King Crab Hack
## An analytical guide to the best bang for tge at the King Crab Shack using Mixed Integer Optimization and Google OrTools

<img src="images/kcs.png" width="1000" >

## Story
Furniture Co’s logistic department of is responsible for the last mile delivery (for more general information, see also [here](https://onfleet.com/blog/what-is-last-mile-delivery/)) from store to customers’ homes. 

## The Menu

| Seafood  | Price $/lb | 
| :------  | ---: | 
| ccm	     |12.99 |
| king	    |	54.99|
| tail_1	  |	26.99|
| tail_2	  |	49.99|
| lob_live |	49.99|
| scallops	|	32.99|
| shrimp_wh|16.99|
| shrimp_hs|18.99|
| snow     |	35.99|
| dungeness|35.99|
| corn     |	0.75|
| potato	  |0.55|
| sausage	 |1.99|


combo	price
combo_1	41.99
combo_1_hs	43.99
combo_2	45.99
combo_3	82.99
combo_4	59.99
combo_4_hs	61.99
combo_5	58.99
combo_6	73.99
combo_6_hs	75.99
combo_dun	54.99
combo_dun_hs	56.99
combo_king	72.99
combo_king_hs	74.99
combo_livlob	62.99
combo_sp1	49.99
combo_sp1_hs	50.99
combo_sp2	39.99
combo_sp2_hs	40.99


## "Build Your Own Bag" or Combos? 


## Mission
Let us generate an assignment schedule for tomorrow by showing "who delivers which furniture". 

## Method
I implement a [Mix Integer Program (MIP)](https://en.wikipedia.org/wiki/Integer_programming) in a Python Jupyter notebook with [Gurobi](https://www.gurobi.com/) as the solver. Adding the following routine is necessary. 

```javascript
import gurobipy as gp
from gurobipy import GRB  
```
 
## Result


## Reference



