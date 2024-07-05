#ESTO ES UN COMENTARIO DE UNA LINEA
'''
- DOCSTRING-
ESTO
ES UN
COMENTARIO DE MÁS
DE UNA LINEA
'''

numero = 120    #TIPO DE DATO ENTERO - int
letra = 'H'     #CARACTER - char
decimal = 65.4  #DECIMAL - float
booleano = True # False (bool) ESTADOS
cadena = "ESTO ES UNA CADENA" #STRING o str

#leer y mostrar informacion
valor_guardado = input("INGRESE CUALQUIER LETRA O PALABRA ")
print(valor_guardado)

print("EL VALOR DE LA VARIABLE ES: ", valor_guardado)
#CONCATENACION
valor1 = "BUENAS"
valor2 = "TARDES"
suma_valores = valor1+" "+valor2
print("LA SUMA ES: ", suma_valores)

#EJERCICIO 1
#CON SUS CONOCIMIENTOS REALICE UNA SUMA DE 2 NÚMEROS INGRESADOS POR TECLADO, POSTERIORMENTE MUESTRE EL RESULTADO

numero1 = input("INGRESE EL PRIMER NUMERO: ")
numero2 = input("INGRESE UN SEGUNDO NUMERO: ")
suma_numeros = numero1 + numero2
print("LA SUMA DE LOS NUMEROS ES: ", suma_numeros)
print(type(suma_numeros))

n = "12"

#CAST
n = int(n)
print(type(n))
n = n + 1000
print("EL RESULTADO DE LA VARIABLE ES: ", n)


numero1 = int(input("Ingrese un numero: "))
numero2 = int(input("Ingrese el segundo numero: "))
suma_numeros = numero1 + numero2
print("EL VALOR DE LA SUMA ES: ", suma_numeros)

#EJERCICIO 2
#CALCULAR EL ÁREA DE UN RECTÁNGULO
longitud = 10
ancho = 5
area = longitud * ancho
print("EL ÁREA DEL RECTÁNGULO ES :", area)

'''
suma +
resta -
multiplicación *
división /
'''

#EJERCICIO 3
#CALCULAR EL PROMEDIO DE 3 NOTAS
nota1 = 4.0
nota2 = 5.9
nota3 = 6.2

suma = nota1 + nota2 + nota3
promedio = suma/3

print("EL PROMEDIO ES DE: ", promedio)

#EJERCICIO 4
#CALCULAR EL COSTO TOTAL DE LOS GASTOS EN COMIDA DE LA MITAD DE UN DIA
pan = 1580
queso = 2000
leche = 1100
completoXL = 2800

gasto_comidas = pan + queso + leche + (completoXL * 2)
print("EL GASTO DE LAS COMIDAS FUE DE: ", gasto_comidas)
print("EL PAN ME COSTÓ: ", pan, " EL QUESO ME COSTÓ: ", queso, " LECHE ME COSTÓ: ", leche)


#EJERCICIO 5
#CALCULAR EL IMPUESTO POR LA COMPRA DE UN CELULAR
valor_telefono = 120000
porcentaje_impuesto = 19
valor_impuesto = (valor_telefono*porcentaje_impuesto) / 100
print("El impuesto es de: ", valor_impuesto)
valor_iva_incl = valor_telefono + valor_impuesto
print("Valor teléfono Iva Incl. ", valor_iva_incl)

#EJERCICIO 6
#UN PANTALON VALE 21990 PERO TIENE UN 40% DE DESCUENTO, CALCULAR VALOR A PAGAR
precio_original = 21990
porcentaje_descuento = 40
descuento_compra = (precio_original * porcentaje_descuento) / 100
precio_final = precio_original - descuento_compra
print("LA COMPRA CON PRECIO ",
       precio_original,
         " con un ",
           porcentaje_descuento,
             "% de descuento, vale: ",
               precio_final)

#CONDICIONALES
mi_bolsillo = 1500
helado_tres_sabores = 1800
dinero_encontrado = 500
mi_bolsillo = mi_bolsillo + dinero_encontrado

if helado_tres_sabores <= mi_bolsillo:
    print("ME ALCANZA PARA COMPRAR UN HELADO")
else:
    print("NO ME ALCANZA")

''' OPERADORES DE COMPARACION
MENOR QUE <
MAYOR QUE >
ES IGUAL A ==
DISTINTO DE !=
____________
MENOR E IGUAL <=
MAYOR E IGUAL >=
'''

#SI EL PATRON DE DESBLOQUEO DE MI TELEFONO ES 2285, INGREA UNA CLAVE Y AUTORIZA SI ESTA ES CORRECTA
clave_telefono = "2285"
clave_ingresada = input("INGRESAR CLAVE: ")

if clave_ingresada == clave_telefono:
    print("SE AUTORIZA EL ACCESO")
else:
    print("CLAVE INVALIDA")

#EJERCICIO DE CONDICIONAL
#SI EL PROMEDIO ES MENOR A 4, REPRUEBO, SINO, APRUEBO EL CURSO
nota1 = 5.0
nota2 = 4.5
nota3 = 7.0
promedio = (nota1 + nota2 + nota3) / 3
if promedio < 4:
    print("REPROBE EL CURSO")
else:
    print("APROBE EL CURSO")
#OPERADORES LÓGICOS
#Y = and
#O = or
#NO = not

if promedio < 4:
    print("REPRUEBO EL CURSO")
else:
    if promedio >= 4 and promedio <= 5.5:
        print("DEBO RENDIR EXAMEN")
    else:
        if promedio > 5.5:
            print("ME EXIMÍ DE DAR EXAMEN")

if promedio < 4:
    print("repruebo el curso")
elif promedio >= 4 and promedio <=5.5:
    print("debo rendir examen")
else:
    print("me eximi")

#EJERCICIO USANDO or
temperatura = 22
#temperatura templada entre 18° y 26°
if temperatura > 18 or temperatura < 26:
    print("TEMPERATURA COMODA")
else:
    print("TEMPERATURA INCOMODA")

hora_7am = 9
hora_8am = 11
hora_9am = 13
hora_10am = 18
hora_11am = 20

#BUCLES

#FOR
"""
temperatura = 0
for numero in range(12):
    print("Ingrese temperatura n° ", numero)
    temperatura = temperatura + int(input())
print("LA SUMA ES: ", temperatura)
print("EL PROMEDIO ES ", (temperatura/12))
"""
#RANGE ( INICIO, TERMINO , PASO )
for numero in range(50, 100, 5):
    print(numero)

for numero in range(100, 0, -1):
    print(numero)

#LISTAS
lista_notas = [3.2, 6.7, 3.4, 5.6, 5.8, 6.9, 7.0]

print("LA NOTA DEL 7MO ESTUDIANTE ES: ", lista_notas[6]) #len(lita_notas)
print(lista_notas)

for indice in range(len(lista_notas)):
    print("NOTA ES: ",lista_notas[indice])

for nota in lista_notas:
    print("NOTA: ", nota)
