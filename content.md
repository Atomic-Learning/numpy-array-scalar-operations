When an arithmetic or comparison operator is used between a NumPy array and a scalar value, NumPy applies the operation between the scalar and **every element** of the array. The array and scalar may appear in either order although, for some operations (like subtraction and division), the order of the operands will affect the result.

```py-cell
import numpy as np

a = np.array([1, 2, 3])
print("a:                    ", a)
print("Addition:             ", 2 + a)
print("Left Subtraction:     ", 2 - a)
print("Right Subtraction:    ", a - 2)
print("Multiplication:       ", a * 2)
print("Left Division:        ", a / 2)
print("Right Division:       ", 2 / a)
print("Left Exponentiation:  ", 2 ** a)
print("Right Exponentiation: ", a ** 2)
print("Left Integer Div:     ", 2 // a)
print("Right Integer Div:    ", a // 2)
print("Left Modulo:          ", 2 % a)
print("Right Modulo:         ", a % 2)
print("Left Greater Than:    ", 2 > a)
print("Right Greater Than:   ", a > 2)
```
