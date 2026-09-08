#assignment2 find the greatest of 3 numbers 
a = float(input('enter any number:'))
b = float(input('enter any number:'))
c = float(input('enter any number:'))
if a >= b and b >= c :
    print(' a is greatest')
elif b >= a and b>=c :
    print('b is greatest')
else :
    print(c, 'is greatest')
    
