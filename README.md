import random #hace posible usar el random
n=int #define "n" como int
nr=int(random.randrange(1,10)) #hace que "nr" sea int y se le asigne el valor random
print("coloca un numero alazar entre 1 y 10") #imprime las instrucciones
while n!=nr: #mientas se cumpla la condicion se repetira esto
    n=input("coloca el numero") #hace posibel asignar valor a "n"
    if n==nr:#si courre pasara la istruccion asiganda
        print("adivinaste el numero")#imprime que adivinaste el numero
        break#rompe el while
    elif n>nr:#si courre pasara la istruccion asiganda
        print("te pasaste")#imprime si te pasaste
    elif n<nr:#si courre pasara la istruccion asiganda
        print("es muy poco")#imprime si es muy poco
        ![image](https://github.com/user-attachments/assets/4935e834-ba46-4a1b-a7df-aa3e9aa8eb5b)
