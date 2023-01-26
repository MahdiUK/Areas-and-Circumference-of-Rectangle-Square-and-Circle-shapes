#Rectangle Area
x = float(input('Enter the width:'))
y = float(input('Enter the length:'))
z = x * y
print(f'Rectangle Area = {z}')

#Square Area
o = float(input('Enter the width:'))
p = float(input('Enter the length:'))
if p > o or o > p:
    print('This is wrong try again')
else:
    h = p * o
    print(f'Square Area = {h}')

#Circle Area
from math import pi
d = float(input('Enter the Radius:'))
f = pi * d * d
print(f'Circle Area = {f}')
