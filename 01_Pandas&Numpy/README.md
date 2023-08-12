# NUMPY!! #
## Why use Numpy Arrays overlists ? ##
1. Numpy is faster as it uses fixed datatypes, whereas lists have multiple datatype storage.
2. Works as a replacement of MATLAB.
3. Plotting
4. Backend
5. Machine Learning

## Using NumPy Arrays: ##
1. import numpy as np
2. a = np.array([1, 2, 3], dtype ='int32') <Single Dimensional Array>
3. b = np.array([1, 2, 3], [4, 5, 6]) <Two Dimensional Array>
4. Use a.ndim to obtain the dimension of an Array and a.shape to obtain the Shape of the Array.
5. a.dtype gives us the type of data being stored.
6. To get the element in (a1, a2, a3, ... ,an), we use Array[a1, a2, a3, a4, ... , an].

### Initialization: ###
1. We use the np.zero((a1, a2, a3 ...)) to generate a zero matrix of the given dimension.
2. np.array([list])
3. np.ones((a1, a2, a3 ...), dtype = '')
4. Array.full((a1, a2, a3 ...), val)
5. np.random.rand(a1, a2, a3, a4, ...)
6. np.identity(n) geneterates a n*n identity Matrix.


# Linear Algebra with Numpy #
## We can multiply two functions with matrix multiplication with the following: np.matmul(a, b)
## Determinant: np.linalg.det(a)
## Similarmly we have Eigen Values, SVD, Inverse, Norm, Trace ...
## If we have function that takes in data-types and we can use this function for Arrays as well. The function is applied element-wise.
