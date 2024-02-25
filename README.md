# Finding-the-Area-of-Circle
# This is a program which providing area of circle for a given radius 
radius = input("Radius of circle is: ")
from math import pi
area = lambda radius: pi * radius ** 2
print("Area of a circle for radius " + str(radius) + " is: ", area(float(radius)))
