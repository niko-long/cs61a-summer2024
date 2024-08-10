# cs61a-summer2024
study notes of ucb cs61a-summer2024 Structure and Interpretation of Computer Programs

**2024/08/19**
- Finished [project1 problem6-7](**https://cs61a.org/hw/sol-hw01/**)  
- time cost: 1.7h.  

```
(miniconda3) (base) niko@NIkodeMacBook-Air hog % python3 ok -q 07
=====================================================================
Assignment: Project 1: Hog
OK, version v1.18.1
=====================================================================

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Running tests

---------------------------------------------------------------------
Test summary
    9 test cases passed! No cases failed.

Backup... 100% complete
```




**2024/08/09**
- Finished [hw01](https://cs61a.org/hw/sol-hw01/)  
- time cost: 1.2h.  
- Test record:  
- <img src="assets/hw01.png" alt="time cost" width="300">  
- Different solution for question Q3: Largest Factor:  
- solution1(official website): highly efficient, only need to calculate the largest factor and return the number.  
```
factor = n - 1
    while factor > 0:
        if n % factor == 0:
            return factor
        factor -= 1
```  
mine:  not efficient, but can store factors in the list
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