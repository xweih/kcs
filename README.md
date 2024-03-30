# The King Crab Hack
## An analytical guide to the best bang for tge at the King Crab Shack using Mixed Integer Optimization and Google OrTools

<img src="images/LMD_Designer_1.png" width="1000" >

## Story
Furniture Co’s logistic department of is responsible for the last mile delivery (for more general information, see also [here](https://onfleet.com/blog/what-is-last-mile-delivery/)) from store to customers’ homes. 

## The Menu

| Seafood | Price/lb | 
| :------ | ---: | 
| India   | 2011 |   
| ccm	    |12.99|
| king	    |	54.99|
| tail_1	    |	26.99|
| tail_2	    |	49.99|
| lob_live	    |	49.99|
| scallops	    |	32.99|
| shrimp_wh	|16.99|
| shrimp_hs	|18.99|
| snow|	35.99|
| dungeness	|35.99|
| corn|	0.75|
| potato	|0.55|
| sausage	|1.99|

![image](https://github.com/xweih/kcs/assets/67345731/fe859d2e-e3fd-4132-87e8-854944e5df05)


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



