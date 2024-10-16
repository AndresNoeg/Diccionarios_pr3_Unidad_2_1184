# Diccionarios_pr3_Unidad_2_1184

# 1.- Divisas

#Se declara un diccionario

divisas={

"€": "Ese simbolo corresponde a euro",

"$":  "Ese simbolo corresponde a dolar",

"¥": "Ese simbolo corresponde a yen"

}

#Se le pide al usuario el simbolo de la divisa

sim=str(input("Ingrese el simbolo de la divisa: "))


if sim=="$":

    print(divisas["$"])
    
elif sim=="€":

    print(divisas["€"])
elif sim=="¥":

    print(divisas["¥"])
else:

    print("Esa divisa no existe")

print(" ")

# 2.- nombre, edad, drieccion

#Se le pide al usuario su nombre edad numero de telefono y direccion

nom=str(input("Ingrese su nombre: "))

age=int(input("Ingrese su edad: "))

direccion_Enrique_Segoviano=str(input("Ingrese su direccion: "))

Num=int(input("Ingrese su numero telefonico: "))

#Se declara un diccionario con las variables

NAD={

    "Nombre": nom,
    
    "Edad" : age,
    
    "Direccion": direccion_Enrique_Segoviano,
    "Numero telefono": Num
}
#Se imprimen varios mensajes y las variables en los diccionarios

print(NAD["Nombre"])

print("Tiene:",NAD["Edad"] )

print("Vive en:", NAD["Direccion"])

print("Su numero de telefono es:",NAD["Numero telefono"])

print(" ")

# 3.- Frutas

# Definir un diccionario con precios de frutas

precios_frutas = {

    'manzana': 2.5,
    
    'banana': 1.2,
    
    'naranja': 3.0,
    
    'fresa': 4.0,
    
    'uva': 5.0
}

# Preguntar al usuario por la fruta y la cantidad de kilos

fruta = input("Ingresa el nombre de la fruta: ").lower()

kilos = float(input("Ingresa la cantidad de kilos: "))

# Verificar si la fruta está en el diccionario

if fruta in precios_frutas:

    precio_kilo = precios_frutas[fruta]
    
    total_precio = precio_kilo * kilos
    
    print("El precio de", kilos ,"kilos de ",fruta, "es: $",total_precio)
    
else:

    print("La fruta", fruta, "no está en el diccionario.")

  ![image](https://github.com/user-attachments/assets/87456caa-1e42-4ec3-8f10-4d0b6514d89c)

  ![image](https://github.com/user-attachments/assets/b5afa610-0ac6-482f-834a-ca24adec7467)




![image](https://github.com/user-attachments/assets/25a8ad49-c0aa-41c4-9f18-50ae71c9fbbe)
