## Problem 1
#### Multiples of 3 and 5
If we list all the natural numbers below ***10*** that are multiples of ***3*** or ***5***, we get ***3***, ***5***, ***6*** and ***9***. The sum of these multiples is ***23***.
Find the sum of all the multiples of ***3*** or ***5*** below ***1000***.

```
def func(m, n):
    i = (m-1) // n
    return i * (i+1) // 2 * n

print(func(1000,3) + func(1000, 5) - func(1000, 15))
```
