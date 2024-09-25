print (" ") #esta variable muestra las comillas para el texto
print ("Salas De La O Cristian David : Mi practica de clase string.py") #esta variable mostrara en la pantalla los datos 
#de la practica
print (" ") #esta variable muestra las comillas para el texto 

import random #esta linea importa el numero random

numero = random.randint(1, 100) #esta linea almacena un numero al azar
adivinanza = int(input("Adivina el numero entre 1 y 100: ")) #esta linea pide adivinar el nuemero al usuario

if adivinanza == numero: #este numero define que hacer si se adivina el numero 
    print("Correcto Has adivinado el numero.") #esta linea muestra las felecidades si se adivina el numero
else: #esta linea dice que hacer si no se cumple 
    print(f"Incorrecto El numero era {numero}.") #esta linea da el aviso que el numero es incorrecto 

print (" ") #esta variable muestra las comillas para el texto 
![image](https://github.com/user-attachments/assets/316bc5aa-6283-4a1e-b098-79f894f3a89b)
![image](https://github.com/user-attachments/assets/fc64fe4b-8f3e-488e-9462-152d0b32e8b4)
