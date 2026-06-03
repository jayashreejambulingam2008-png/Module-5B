```
DONE BY: JAYASHREE J
REGISTER NUMBER: 212225040145

```
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

arr = np.array([[9, 3, 5],
                [2, 8, 1],
                [7, 4, 6]])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```
## Output
<img width="916" height="436" alt="image" src="https://github.com/user-attachments/assets/875df14e-1b27-43ae-9bba-333d89ea7e47" />

## Result
Hence the task to write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order has been done successfully.

# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

```
import numpy as np

x = np.array([21, 64, 86, 22, 74, 55, 81, 79, 90, 89])
y = np.array([21, 7, 3, 45, 10, 29, 55, 46, 63, 12])

indices = np.where(x >= y)

print("Indices where x >= y:")
print(indices)
```
## Output

<img width="919" height="205" alt="image" src="https://github.com/user-attachments/assets/caf2fc3c-42e5-4602-b434-157854700b5d" />

## Result
Hence the task  write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y` has been done successfully.

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
```
import numpy as np

arr = np.array([[10, 20, 30],
                [40, 50, 60],
                [70, 80, 90]])

new_col = np.array([100, 200, 300])

arr = np.delete(arr, 1, axis=1)
arr = np.insert(arr, 1, new_col, axis=1)

print("Updated Array:")
print(arr)
```
## Output
<img width="927" height="295" alt="image" src="https://github.com/user-attachments/assets/5be98798-a77a-4cb0-a60d-c9ca2b3f2186" />

## Result
Hence the task to write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position has been done successfully.


