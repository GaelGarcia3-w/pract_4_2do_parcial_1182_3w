# pract_4_2do_parcial_1182_3w
Edgar Gael Garcia Camacho 3-W
# Act.1
print(" ")

print("Edgar Gael Garcia camacho 1182:Pract_4 ")

print(" ")

#Se agrega un diccionario vacío.

Diccionario ={}

print(" ")

#se agrega el nombre del usuario.

lo=str(input("Ingresa tu nombre :"))

print(" ")

Diccionario["Nombre"] = lo

print(Diccionario)

#se agrega la edad del usuario.

print(" ")

Edad =int(input("Ingresa tu edad :"))

print(" ")

Diccionario["Edad"] = Edad

print(Diccionario)

#Se agrega el genero del usuario.

print(" ")

Sexo =str(input("Ingresa tu sexo :"))

print(" ")

Diccionario["Sexo"] = Sexo

print(Diccionario)

#se agrega el numero telefnico.

print(" ")

Telefono = int(input("Ingresa tu numero telefonico :"))

print(" ")

Diccionario["Telefono"] = Telefono

print(Diccionario)

#Se agrega el correo del usuario

def email_si(Correo):
    return "@" in Correo 

print(" ")

Correo =input("Ingresa tu correo :")

print(" ")

Diccionario["Correo"] = Correo 

print(Diccionario)

![image](https://github.com/user-attachments/assets/df2f22b7-b57f-4bb0-a7ea-394d4c730c97)

![image](https://github.com/user-attachments/assets/772aa911-1e06-4d75-b3d3-73ff7aaa2b4f)

# Act.2

print(" ")

print("Edgar Gael Garcia Camacho 1182:Pract_4")

print(" ")

#Se crea un diccionario.

Diccionario ={

"Cama" : "Bed",

"Comida" : "Food",

"Lapíz" : "Pincel",

"Manzana" : "Apple",

"Galletas" : "Cookies",

"Mano" : "Hand"

}

#Te solicita introducir una palabra para traducirla.

Pal = str(input("Ingresa una palabra para traducirla :"))

#Traduce la palabra seleccionada o te dice que la palabra no esta en el diccionario.

if Pal in Diccionario:

print(Diccionario[Pal])

else:

print("Esa palabra no esta en el diccionario.")

![image](https://github.com/user-attachments/assets/6c9d35e7-16a7-4b19-8f69-d597e609425d)

![image](https://github.com/user-attachments/assets/5eb91239-4885-4e2c-b6d3-bcdab0262eb8)

