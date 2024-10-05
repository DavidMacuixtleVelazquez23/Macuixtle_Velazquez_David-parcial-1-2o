#Aqui se importa "random"
print("Macuixtle Velazquez David\n")
import random   
#Aqui se imprime un mensaje el cual te indica que introduzca un numero
print("Cuales son los numeros triunfadores de la loteria?\n")
#Aqui se inicia una variable la cual guardara el numero escrito
#Aqui podremos escribir numeros gracias a "int"
num1 = int(input("Cual es el numero? "))
num2 = int(input("Cual es el numero? "))
num3 = int(input("Cual es el numero? "))
num4 = int(input("Cual es el numero? "))
num5 = int(input("Cual es el numero? "))
#Aqui se guardan las varibles en lista
loteria = ([num1,num2,num3,num4,num5])
#.sort nos permite mostrar los numeros de menor a mayoe
loteria.sort()
#Aqui se imprime un texto
print("\nGracias por introducir los numeros\nA continuacion se mostraran en orden\n")
#aqui se imprime la variable ya guardada para mostrar los numeros en orden
print(loteria,"\n")
#Aqui se delclara otra variable pero esta vez contiene random
#Esto nos ayuda a que escoja un numero al alzar
Item = random.choice(loteria)
#Aqui se imprime la variable item la cual ya se habra decidido que numero al alzar se va a imprimir
print("\nEl numero ganador definitivo es : "), print(Item)

![image](https://github.com/user-attachments/assets/2d1055bc-b85a-4860-9022-0ea64f363777)
![image](https://github.com/user-attachments/assets/80bb5b4b-605d-4c9c-8630-3605ed9e2013)
