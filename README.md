1. MENÚ (BASE DE TODO)
datos = []

while True:
    print("1. Opción 1")
    print("2. Opción 2")
    print("3. Salir")

    opcion = input("Elige: ")

    if opcion == "1":
        pass
    elif opcion == "2":
        pass
    elif opcion == "3":
        break
    else:
        print("Opción inválida")
🔹 2. FUNCIONES
def funcion():
    print("Hola")

Llamar función:

funcion()
🔹 3. INPUT + TIPOS
nombre = input("Nombre: ")
edad = int(input("Edad: "))
precio = float(input("Precio: "))
🔹 4. TRY / EXCEPT (VALIDACIÓN)
try:
    edad = int(input("Edad: "))
except:
    print("Error")
    return
🔹 5. LISTAS (LO MÁS IMPORTANTE)
datos = []

datos.append("Juan")

for d in datos:
    print(d)
🔹 6. DICCIONARIOS (SUBE NOTA)
persona = {
    "nombre": "Juan",
    "edad": 20
}

Guardar en lista:

datos.append(persona)

Mostrar:

for p in datos:
    print(p["nombre"], p["edad"])
🔹 7. TUPLAS (SI TE LAS PIDEN)
tupla = ("Juan", 20)

datos.append(tupla)

Mostrar:

for t in datos:
    print(t[0], t[1])
🔹 8. CÁLCULOS (TOTAL, PROMEDIO, ETC)
total = 0

for d in datos:
    total += d["precio"] * d["cantidad"]

print(total)
🧪 CASOS HIPOTÉTICOS (LO QUE TE PUEDEN PONER)
🟢 CASO 1: INVENTARIO (EL MÁS COMÚN)

👉 Usa: lista + diccionario

producto = {
    "nombre": nombre,
    "precio": precio,
    "cantidad": cantidad
}
🟡 CASO 2: REGISTRAR PERSONAS

👉 Opción 1 (PRO):

persona = {"nombre": nombre, "edad": edad}

👉 Opción 2 (fácil):

datos.append(nombre)
🔵 CASO 3: SOLO LISTA SIMPLE

👉 Si no te piden mucho:

datos.append(input("Dato: "))
🟣 CASO 4: TUPLAS

👉 Si dicen “usar tuplas”:

tupla = (nombre, edad)
datos.append(tupla)
🔴 CASO 5: ESTADÍSTICAS

👉 Suma:

total += valor

👉 Promedio:

promedio = total / len(datos)
🧠 CÓMO SABER QUÉ USAR
Si te piden…	Usa…
varios datos (nombre, precio)	diccionario
datos simples	lista
obligatorio tupla	tupla
calcular cosas	for + acumulador
🔥 FRASES PARA LA SUSTENTACIÓN

Di esto y quedas pro:

“Usé funciones para modularizar el código”
“Utilicé listas para almacenar datos”
“Implementé diccionarios para estructurar la información”
“Validé datos con try/except”
🚀 ESTRUCTURA FINAL (TODO JUNTO)
datos = []

def agregar():
    pass

def mostrar():
    pass

def calcular():
    pass

while True:
    opcion = input("Elige: ")

    if opcion == "1":
        agregar()
    elif opcion == "2":
        mostrar()
    elif opcion == "3":
        calcular()
    elif opcion == "4":
        break
💥 CONSEJO FINAL

Si te bloqueas:

👉 pide input
👉 guarda en lista
👉 imprime

YA con eso pasas.

Si quieres, compae, te hago una versión:
📄 “mini acordeón de 1 hoja” para copiar literal

o te hago otro caso más difícil pa que quedes fino 😈
📘 🧠 DEFINICIONES + CÓDIGO
🔹 1. VARIABLES Y TIPOS DE DATOS
📌 Definición:

Una variable es un espacio donde guardas información.

📌 Tipos:
int → enteros
float → decimales
str → texto
bool → verdadero/falso
✅ Código:
nombre = "Juan"     # string
edad = 18           # int
precio = 10.5       # float
activo = True       # boolean
🔹 2. OPERADORES
📌 Definición:

Sirven para hacer cálculos y comparaciones.

📌 Tipos:
Aritméticos: + - * /
Comparación: == != > <
Lógicos: and or not
✅ Código:
if edad >= 18 and activo:
    print("Puede entrar")
🔹 3. ESTRUCTURAS DE CONTROL
🔸 CONDICIONALES
📌 Definición:

Permiten tomar decisiones.

✅ Código:
if edad >= 18:
    print("Mayor de edad")
elif edad == 17:
    print("Casi")
else:
    print("Menor")
🔸 BUCLES
📌 Definición:

Repiten código varias veces.

🔹 WHILE
while True:
    opcion = input("Elige: ")
    if opcion == "4":
        break
🔹 FOR
for i in range(5):
    print(i)
🔹 4. FUNCIONES
📌 Definición:

Bloques de código reutilizables.

✅ Código:
def saludar():
    print("Hola")

saludar()
🔹 Con parámetros
def suma(a, b):
    return a + b
🔹 Lambda (simple)
suma = lambda a, b: a + b
🔹 5. ESTRUCTURAS DE DATOS
🔸 LISTAS
📌 Definición:

Guardan varios datos.

datos = []
datos.append("Juan")

for d in datos:
    print(d)
🔸 TUPLAS
📌 Definición:

Como listas pero no cambian.

tupla = ("Juan", 20)
print(tupla[0])
🔸 DICCIONARIOS
📌 Definición:

Guardan datos con clave y valor.

persona = {
    "nombre": "Juan",
    "edad": 20
}
🔹 6. MANEJO DE ERRORES
📌 Definición:

Evita que el programa se rompa.

try:
    edad = int(input("Edad: "))
except:
    print("Error")
🔹 7. BUENAS PRÁCTICAS
📌 Definición:

Forma correcta de organizar el código.

✔ usar funciones
✔ comentar
✔ separar lógica

# función para agregar
def agregar():
    pass
🧪 CÓMO APLICAR TODO (EJEMPLO REAL)
datos = []

def agregar():
    try:
        nombre = input("Nombre: ")
        edad = int(input("Edad: "))
    except:
        print("Error")
        return

    persona = {"nombre": nombre, "edad": edad}
    datos.append(persona)

def mostrar():
    for p in datos:
        print(p["nombre"], p["edad"])

while True:
    print("1. Agregar")
    print("2. Mostrar")
    print("3. Salir")

    opcion = input("Elige: ")

    if opcion == "1":
        agregar()
    elif opcion == "2":
        mostrar()
    elif opcion == "3":
        break
🧠 RESUMEN ULTRA RÁPIDO (POR SI TE PREGUNTAN)
Variable → guarda datos
If → toma decisiones
While → repite
Función → organiza código
Lista → guarda muchos datos
Diccionario → datos con nombre
Try/except → evita errores
🚀 CONSEJO FINAL

Si te preguntan teoría:
👉 responde definición + ejemplo corto

Si te ponen código:
👉 usa menú + funciones + lista
