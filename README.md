# dimpy
A python package for creating N-dimensional array in user friendly manner

Install command: 
---------------
`pip install dimpy`


Use example:
------------
```
import dimpy as dp  # Import package as an object dp
testarray=dp.dim(5,7,9)  # This will create a 3 dimensional array consisting of 5x7x9 elements. You may give any number of inputs separated by comma. 
testarray[2][3][5]= 'Hello' # Let us replace (or do anything else) just one element. All other values will be 0 by default.
print(testarray)
dp.dfv(testarray,'x')  # We can change the default value by anything (e.g. 'x' here) 
print(testarray)
# Below steps are optional 
testarray=dp.npary(testarray) # This will change the type of the array from 'list' to 'numpy.ndarray'
testarray[1,4,3]=5 # Now work with elements in numpy style
print(testarray)
```

For details please follow the link https://www.researchsquare.com/article/rs-1004075/v2
