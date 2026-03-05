# Aim  

The aim of this program is to study and demonstrate the basic features of the **NumPy** library in Python, including array creation, determining dimensions and shape, identifying data types, using built-in array generation functions, and performing mathematical and statistical operations on arrays.

---

# Theory  

**NumPy (Numerical Python)** is a powerful Python library used for numerical computing. It provides support for multi-dimensional arrays and matrices, along with a large collection of mathematical functions to operate on these arrays efficiently.

## 1. Array Creation  
Arrays in NumPy are created using `np.array()`.  
- `a` is a one-dimensional (1D) array.  
- `b` is a two-dimensional (2D) array (matrix).  

## 2. Dimension of Array  
The `ndim` attribute is used to determine the number of dimensions of an array.  
- A 1D array has dimension 1.  
- A 2D array has dimension 2.  

## 3. Shape of Array  
The `shape` attribute returns a tuple representing the size of the array in each dimension.  
- For a 1D array, it shows the number of elements.  
- For a 2D array, it shows the number of rows and columns.  

## 4. Data Type  
The `dtype` attribute shows the data type of the elements stored in the array (e.g., integer, float).

## 5. Built-in NumPy Functions  
NumPy provides several in-built functions to generate arrays:  
- `np.zeros((2,3))` → Creates a 2×3 array filled with zeros.  
- `np.ones((3,3))` → Creates a 3×3 array filled with ones.  
- `np.eye(3)` → Creates a 3×3 identity matrix.  
- `np.arange(1,10,2)` → Generates values from 1 to 9 with a step of 2.  
- `np.linspace(0,1,4)` → Generates 4 equally spaced values between 0 and 1.  

## 6. Operations Using NumPy  
NumPy allows element-wise mathematical operations:  
- `a + 5` → Adds 5 to each element of array `a`.  
- `b * 2` → Multiplies each element of array `b` by 2.  

It also provides statistical functions such as:  
- `np.mean(a)` → Calculates the mean (average).  
- `np.median(a)` → Calculates the median.  
- `np.min(a)` → Finds the minimum value.  
- `np.max(a)` → Finds the maximum value.  
- `np.sum(a)` → Calculates the sum of all elements.  

---

# Conclusion  

From this program, we understand how to create and manipulate arrays using NumPy. We learned how to determine the dimension, shape, and data type of arrays, generate special arrays using built-in functions, and perform arithmetic and statistical operations efficiently. NumPy simplifies numerical computations and is highly useful for data analysis, scientific computing, and machine learning applications.
