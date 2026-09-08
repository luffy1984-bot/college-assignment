# assignment3 write a program that indicates it is a right angle triangle
a = int(input('enter the length of the side'))
b = int(input('enter the length of the side'))
c = int(input('enter the length of the side'))

if a**2+b**2==c**2 or a**2+c**2==b**2 or b**2+c**2==a**2:
    print('it is a right angle triangle')
else:
    print('invalid triangle')
