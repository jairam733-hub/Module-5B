# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

Add code here
```
import numpy as np
d=np.array([[3,2,8],[4,12,34],[23,12,67]])
f=np.array([2,1,8])
print("Before inserting new column","\n",d)
a=np.insert(d,3,f,axis=1)
print("After inserting new column","\n",a)
```

## Output
<img width="1920" height="1080" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/da9e5de5-fc54-4ff4-80a6-877648d17a7c" />

## Result
