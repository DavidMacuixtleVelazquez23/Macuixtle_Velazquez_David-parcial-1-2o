#Aqui se define una funcion
print("Macuixtle Velazquez David\n")
def MOSTRAR_MATERIAS(thislist):
    #Aqui se inicia una secuencia for que nos permitira mostrar un texto antes de cada materia
    for materia in thislist:
        #Aqui se imprime el mensaje donde despues pone la varible materia
        #Esto para mostra cada una de la lista y no la lista entera
        print("estoy cursando: ", materia)

#Aqui se declaran las variables las cuales guardarn el texto introducido
materias = input("Escribe la primer materia: ")
materias1 = input("Escribe la segunda materia: ")
materias2 = input("Escribe la tercer materia: ")
materias3 = input("Escribe la cuarta materia: ")
materias4 = input("Escribe la quinta materia: ")
#Aqui se declara una variable que contiene a modo de lista las demas variables
thislits = ([materias,materias1,materias2,materias3,materias4])
#Aqui se imprime la lista gracias a print()
print("\n",thislits) 
MOSTRAR_MATERIAS(thislits)

![image](https://github.com/user-attachments/assets/c8613580-61c6-4b61-8b56-514921054f00)
