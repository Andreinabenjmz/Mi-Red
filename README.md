# Mi-Red
Intentaré guardar mis avances aquí

print("Bienvenido a ... ")
print("""           _                _ 
          (_)              | |
 _ __ ___  _   _ __ ___  __| |
| '_ ` _ \| | | '__/ _ \/ _` |
| | | | | | | | | |  __/ (_| |
|_| |_| |_|_| |_|  \___|\__,_| """)

#Primera interacción: Solicitamos al usuario que ingrese su nombre, y lo guardamos en una variable de tipo str
nombre = input("Para empezar, dime cómo te llamas")
print()
print("Hola ", nombre, ", bienvenido a Mi Red")
print()

#Segunda interacción: Solicitamos el ingreso del año y tuilizamos este dato para estimar la edad de la persona
año = int(input("Para preparar tu perfil, dime en qué año naciste. "))
edad = 2021-año-1

#Tercera interacción: Solicitamos la altura en metros
estatura = float(input("Cuéntame más de ti para agregarlo a tu perfil. ¿Cuánto mides? Dámelo en metros. "))
estatura_m = int(estatura)
estatura_cm = int((estatura - estatura_m)*100)

#Cuarta interacción: Consultamos cuántos amigos tiene el usuario
num_amigos = int(input("Muy bien. Cuéntame cuántos amigos tienes. "))

#Tarea_Quinta interacción: Solicitamos nombre de la ciudad donde vive
ciudad = input("Ahora dime en qué ciudad vives. ")

#Tarea_Sexta interación: Preguntamos la lengua materna
idioma_nativo = input("¿Cuál es tu lengua nativa?")

#Tarea_Séptima interacción: Preguntamos cuáles idiomas desea aprender
idiomas_nuevos = input("¿Qué idiomas te gustaría aprender?")

#Con los datos recolectados escribimos en pantalla un texto que resuma los datos que hemos obtenido
print()
print("Muy bien ", nombre, ". Entonces podemos crear un perfil con estos datos.")
print("--------------------------------------------------")
print("Nombre:  ", nombre)
print("Edad:    ", edad, "años")
print("Estatura:", estatura_m, "metros y", estatura_cm, "centímetros")
print("Amigos:  ", num_amigos)
print("Ciudad actual: ", ciudad)
print("Idioma nativo: ", idioma_nativo)
print("Idiomas que quiero aprender: ", idiomas_nuevos)
print("--------------------------------------------------")
print("Gracias por la información. Esperamos que disfrutes con Mi Red")
print()

#Finalmente, solicitamos un mensaje de prueba que sirva para publicar un estado del usuario.
mensaje = input("Ahora vamos a publicar tu primer mensaje. ¿Qué piensas hoy? ")
print()
print("--------------------------------------------------")
print(nombre, "dice:", mensaje)
print("--------------------------------------------------")
