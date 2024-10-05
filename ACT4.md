#Aqui se define una funcion
print("Macuixtle Velazquez David\n")
def MOSTRAR_MATERIAS(thislist):
    #Aqui se inicia una secuencia for que nos permitira mostrar un texto antes de cada materia
    for materia in thislist:
        #Aqui se imprime el mensaje donde despues pone la varible materia
        #Esto para mostra cada una de la lista y no la lista entera
        #poner materia[0] y materia[1] sirve para que se muestre lo siguiente
        #Materia[0] mostrara el nombre de la materia
        #materia[1] mostrara la calificacion
        print("estoy cursando: ", materia[0], " y has obtenido: ", materia[1])
#Aqui se declaran las variables las cuales guardarn el texto introducido
#Ahora depues del primer texto introducido, te va a pedir que ingreses la calificacion
#Esto colocando ",int(input())" en la misma linea de codigo. La coma ayuda a que no colapce
#Esto hace que se guarde como la misma variable pero en lista por decirlo de alguna manera
#[MATERIA,CALIFIACION] asi queda por asi decirlo
materias = input("Escribe la primer materia: "), int(input("Escribe la calificacion: "))
materias1 = input("Escribe la segunda materia: "), int(input("Escribe la calificacion: "))
materias2 = input("Escribe la tercer materia: "), int(input("Escribe la calificacion: "))
materias3 = input("Escribe la cuarta materia: "), int(input("Escribe la calificacion: "))
materias4 = input("Escribe la quinta materia: "), int(input("Escribe la calificacion: "))
#Aqui se declara una variable que contiene a modo de lista las demas variables
thislits = ([materias,materias1,materias2,materias3,materias4])
#Aqui se imprime la lista gracias a print()
print("\n",thislits) 
#Esta parte imprime la lista y el texto anteriormente mencionado
MOSTRAR_MATERIAS(thislits)  

![image](https://github.com/user-attachments/assets/08088507-ea7d-484d-b13f-a62669788884)
![image](https://github.com/user-attachments/assets/2ab51fce-7a7a-4539-8734-6ce3252627e3)

