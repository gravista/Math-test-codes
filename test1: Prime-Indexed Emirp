def prime(x):
    if x < 2:
        return False
    for i in range(2, int(x**0.5) + 1):
        if x % i == 0:
            return False
    return True

def emirp(x):
    return prime(x) and prime(int(str(x)[::-1]))

def nom(x):
    nom=0
    for i in range(0, x):
        if prime(i)==True:
            nom+=1
    return nom
x=0
while True:
    x += 1
    if prime(x)==True and emirp(x)==True and prime(nom(x))==True and emirp(nom(x))==True:
        print(f'{x} is Prime-Indexed Emirp')
