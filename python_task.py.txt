import random

C = 0

while C != 4:
    A = random.randrange(0, 9)
    B = random.randrange(0, 9)
    C = A * B
    print('A=', A)
    print('C=', C)
    print('')
else:
    print('Success!')
    print('A=', A)
    print('B=', B)