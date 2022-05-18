In this section, we will discuss Python NumPy shape function.
The numpy module provides a shape function to represent the shape and size of an array. The shape of an array is the no. of elements in each dimension.
In NumPy, we will use a function called shape that returns a tuple, the elements of the tuple give the lengths of the array dimensions.
The shape attribute always returns a tuple that represents the length of each dimension. The 1-d array is a row vector and its shape is a single value sequence followed by a comma. One-d arrays don’t have rows and columns, so the shape function returns a single value tuple.
he term broadcasting refers to the ability of NumPy to treat arrays of different shapes during arithmetic operations. Arithmetic operations on arrays are usually done on corresponding elements. If two arrays are of exactly the same shape, then these operations are smoothly performed.

Example 1
Live Demo
import numpy as np 

a = np.array([1,2,3,4]) 
b = np.array([10,20,30,40]) 
c = a * b 
print c
Its output is as follows −
1)What makes numpy. shape()different from numpy.size()?

A)Shape() is used to get complete structural shape of our 2Darray. For example(3,4). np. size() will give us how many elements are present in total.

2)In Numpy, describe the idea of broadcasting?

A) The term broadcasting refers to ability of Numpy to treat arrays Of different shapes during arthimetic operations. Arthimetic operations on arrays are usually done on corresponding elements. If two arrays are of exactly the same shape, then these operations are smoothly performed.

3)What makes python better than other libraries for numerical computation?

A)One of the key features of python is its numerous libraries and packages. Some are written in given below.

1)SciPy: The SciPy package includes algorithms and functions which are crux of python scientific computing capabilities.
