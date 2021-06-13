# cvxpy
## Using cvxpy library, write a scrit for finding solution to a following problem:

Our mobile factory makes three types of phones (lets call them A, B, C).

profit per phone type A will be constant for every following month (variable price_a)
profit per phone type B will be lowering every month, because it is an old model and people will be buying less so the overall price will have to be lower. Profit per phone type B is in variable price_b.
profit per phone type C on the other hand will go up. It is new model and company expect to rapid improvement in technology (mostly lowering the manufacturing costs), variable price_c.
Factory limitations:

factory is not able to produce more then 10000 mobile phones per month
every production line is different. Thus every month at least 2000 of mobile phone of each type has to be made
I the second half of the year, manufactured mobile phones of type C can NOT be more than 5000 per month
mobile phones type B can NOT be greater than 4500 per month
in the first half of the year quantity of mobile phones of type A can NOT exceed 4000 per month
Your task is to make a schedule for every type of mobile phone for every month in the followting year to maximize profit of a whole factory. That mean you will have 3 numbers (type A, B and C) for every month (12 months).

What will be the profit of a whole factory next year?

## Getting started
On Window:
 
Install cvxpy

```bash
$ python -m pip install cvxpy
``` 
** Visual Studio Builder version **

Install numpy


```bash
$ python -m pip install numpy
``` 
Install matplotlib

```bash
$ python -m pip install matplotlib
``` 
## Initial data
```bash
price_a = np.full(12, 325.)
price_b = np.array([300, 300, 290, 275, 275, 280, 260, 250, 230, 200, 210, 190.])
price_c = np.array([100, 110, 98, 115, 200, 220, 210, 500, 500, 490, 487, 550.])
```
## Running script

```bash
python cvxpy_example.py
``` 
(Python 3.9.0)

__ tao @ 2021 04 25 __
