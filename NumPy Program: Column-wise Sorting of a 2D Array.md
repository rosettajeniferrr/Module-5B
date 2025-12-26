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
```
import numpy as np
n=eval(input())
array=np.array(n)
print("Given array")
print("",array)
print()
sorted=np.sort(array)
print(sorted)
```
## Output
<img width="677" height="217" alt="image" src="https://github.com/user-attachments/assets/b7699847-18dd-4971-89f9-7ca0fbf96d0c" />

## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.
