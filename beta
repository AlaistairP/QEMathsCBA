#QE = ax**2 + bx + c = 0

import numpy as np
import math
import matplotlib.pyplot as plt
from math import sqrt

check_input = True
while check_input:
    a, b, c = eval(input("Please enter the a, b, c coefficients of your quadratic equation: "))
    try: 
        float(a), float(b), float(c)
        check_input = False
    except ValueError:
        print("Please make sure the coefficients are real numbers and try again")
        check_input = True

disc = b*b-4*a*c

if disc >=0:
    x1 = (-b+sqrt(disc))/(2*a)
    x2 = (-b-sqrt(disc))/(2*a)
    print("The roots of the equation are:", x1, x2)
else:
    print("The equation has no solutions")


   
    x = np.linspace(-10, 15)
    y = x**2 - 5*x -14

plt.hlines(y=0, xmin=min(x), xmax=max(x), linestyles='dashed')
plt.vlines(x=0, ymin=min(y), ymax=max(y), linestyles='dashed')
plt.xlabel('x')
plt.ylabel('y')

plt.plot(x, y)
plt.show()




