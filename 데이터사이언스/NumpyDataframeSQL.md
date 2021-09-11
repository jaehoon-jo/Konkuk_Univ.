# Numpy Dataframe SQL

## Numpy
- Homogeneous, multidimensional array
- Ndarray (or array)
    - ndim (차원)
    - shape (각 차원의 element 수 구성)
    - size (element 수)
    - dtype (element 타입)
    - itemsize (각 element들의 bit 수)

## ndarrary attributes
```py
import numpy as np
a = np.arange(15).reshape(3,5)
print(a)
# [[0 1 2 3 4] [5 6 7 8 9] [10 11 12 13 14]]
print(a.shape)
# (3, 5)
print(a.ndim)
# 2
print(a.dtype.name)

print(a.itemsize)

print(a.size)

print(type(a))

```