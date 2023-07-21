# algo-linear-programming

Author:  Erin James Wills, ejw.data@gmail.com  

![Linear Programming](./images/linear-programming.png)  

<cite>Photo by <a href="https://unsplash.com/@marcinjozwiak?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Marcin Jozwiak</a> on <a href="https://unsplash.com/s/photos/logistics?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></cite>

<br>

## Overview  
Linear programming examples using Excel and Python

## Excel Simulations  
1.  `constrained-linear-equations.xlsx` - Selecting product quantity to produce maximize profits and keeping with raw material inventory.
1.  `transportation-goods.xlsx` - Selecting factory production and shipments of each product to each country while minimizing cost, meeting demand, and not exceeding factory capacity.  
1.  `adv-transportation-goods.xlsx` - work in progress
1.  `production-scheduling.xlsx` - Determining production and inventory amounts based on minimizing operational expenses while operating within production capacity and at least meeting demand.

<br>

## Python Simulations  
1.   `linear-optimization.ipynb` - Python PuLP library version of the Excel `constrained-linear-equations.xlsx`
1.  `linear-optimization-shipping.ipynb` - Python PuLP library version of the Excel `transportation-goods.xlsx`
1.  `linear-optimization-shipping-pandas.ipynb` - modified version of `linear-optimization-shipping.ipynb` that utilizes pandas dataframes to access data instead of generating lists.
1.  `linear-optimization-warehousing.ipynb` - work in progress  
1.  `production-scheduling.ipynb` - Python PuLP library version of Excel `production-scheduling.xlsx`
1.  `production-scheduling-sensitivity.ipynb` - modified version of `production-scheduling.ipynb` that allows for a list of any any user supplied variable to be substituted.  The outcomes are plotted on to allow easy analysis of the effects of variable changes.  
  

### Technologies
* Excel
* Python PULP
### Improvements
* add visualization of Excel and Python answers
