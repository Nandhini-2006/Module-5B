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
~~~
import numpy as np
a = np.array(eval(input()))
print("Printing Original array")
print(a)
sorted_by_row = a[:, a[1].argsort()]
print("Sorting Original array by second row")
print(sorted_by_row)
sorted_by_col = a[a[:, 1].argsort()]
print("Sorting Original array by second column")
print(sorted_by_col)
~~~
## Output

<img width="1185" height="849" alt="image" src="https://github.com/user-attachments/assets/fc0c7e99-ec36-496d-9129-867cc7d151fa" />

## Result
Thus the NumPy program that sorts the elements of a given 2D array in ascending order is executed successfully.
