#write a code to calculate the area and circumference of a circle by taking a manual radius and assinging the pi value with 3.14159 r=7.5
pi=3.14159
r=float(input("enter the radius:"))
a=pi * (r**2)
c=2* pi* r
print("area:",a)
print("circumference:",c)


#trignometric functions
from math import sin,cos,tan,radians
angle=30
print("sin:",sin(radians(angle)))
print("cos:",cos(radians(angle)))
print("tan:",tan(radians(angle)))


from math import floor, ceil
num=7.9
print("floor:",floor(num))
print("ceil:",ceil(num))
