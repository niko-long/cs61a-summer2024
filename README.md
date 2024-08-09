# cs61a-summer2024
study notes of ucb cs61a-summer2024 Structure and Interpretation of Computer Programs


**2024/08/09**
- Finished [hw01](https://cs61a.org/hw/sol-hw01/)  
- time cost: 1.2h.  
- Test record:  
- <img src="assets/hw01.png" alt="time cost" width="300">  
- Different solution for question Q3: Largest Factor:  
```
factor = n - 1
    while factor > 0:
        if n % factor == 0:
            return factor
        factor -= 1
```  
mine:  
```
    m = []
    for i in range(1, n-1):
        if n % i ==0 :
            m.append(i)
    return max(m)

```
**2024/08/09**
- Finished [lab00](https://cs61a.org/lab/lab00/)  
- time cost: 5min