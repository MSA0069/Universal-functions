# Broadcasting
import numpy as np
arr2D = np.array([[10, 20, 30], [40, 50, 60]])

print("Array + 10:\n", arr2D + 10)

arrC = np.array([1, 2, 3])

print("Broadcasted Addition:\n", arr2D + arrC)

O/P:

Array + 10:

[[20 30 40]

[50 60 70]]

Broadcasted Addition:

[[11 22 33]

[41 52 63]]
