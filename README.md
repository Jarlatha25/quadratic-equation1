# quadratic-equation1
.Write a python program to calculate the roots of a given quadratic equation.

import math
a=int(input("Enter a"))
b=int(input("Enter b"))
c=int(input("Enter c"))
d=(b*b)-(4*a*c)
if d>=0:
    print("roots are : ")
    x1=-b+math.sqrt(d)/(2*a)
    x2=-b-math.sqrt(d)/(2*a)
    print(" x1 = =", x1)
    print(" x2 = =", x2)
else:
        print("roots are imaginary.")

Output:
Enter a4
Enter b5
Enter c2
roots are imaginary.
