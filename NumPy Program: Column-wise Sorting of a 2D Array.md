# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
Add code here
```
import numpy as np
d=np.array([[3,2,8],[4,12,34],[23,12,67]])
f=np.array([2,18,32])
print("Before inserting new column","\n",d)
a=np.insert(d,3,f,axis=1)
print("After inserting new column","\n",a)
```
## Output
<img width="1920" height="1080" alt="Screenshot (138)" src="https://github.com/user-attachments/assets/68c8375f-595f-4058-8483-cb841b80e4b7" />

## Result
