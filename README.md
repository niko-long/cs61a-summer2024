# cs61a-summer2024
study notes of ucb cs61a-summer2024 Structure and Interpretation of Computer Programs


**2024/08/17**
- Project1-Hog Finished, all points got.  
- Finished [project1 problem 8-11.](**https://cs61a.org/hw/sol-hw01/**) 
- <img src="assets/project1_finished.png" alt="time cost" width="300">
- time cost: 2.2h.
- <img src="assets/project1_time.png" alt="time cost" width="300">
- time cost for project1:6.8h

**2024/08/12** 
- Finished [project1 problem2-5.](**https://cs61a.org/hw/sol-hw01/**) Spent some time to debug an error in problem4 but found when trying to solve problem5.  
- <img src="assets/project1-5.png" alt="time cost" width="300">
```
if num_factors(score) == 3 or 4:
```  
- this syntax will cause the condition to always be True because 4 itself is a non-zero value, which is considered True in Python. 
- time cost: 1.9h.



**2024/08/11**
- Finished Lecutre_objects.  
- Finished [project1 problem1.](**https://cs61a.org/hw/sol-hw01/**) Spent quite some time to understand question description(I thought I could finish the first question in 5 minutes!), the  good point is that I deepen my understanding of high order function through this process.  
- Test record:  
- <img src="assets/project1-1.png" alt="time cost" width="300">
- time cost: 1h. 



**2024/08/10**
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