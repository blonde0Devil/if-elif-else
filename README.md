v = 5

if v == 0:
    v = 1
    print('v=0')

elif type(v) == type(5) or type (v) == type(5.5):
    print ('x допустимое значение')

else:
    print('это был другой  тип данных')
    v = 1 


print(100/v)
