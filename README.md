prueba
======

elio rios CI:20894798

# Realizar un programa que permita hacer uso de las operaciones matemáticas básicas y además exponentes y raíces

def exponente(x, e):
    return x**e

def raiz(x):
    import math

    return math.sqrt(x)

def suma(x,y):
    return x+y

def resta(x,y):
    return x-y
    
def multiplica(x,y):
    return x*y
    
def divide(x,y):
    if y > 0:
        return x/y
    else: 
        print 'No es divisible, es infinito'

mensaje = "PROG OPERACIONES BASICAS"
menu = "6. SUMAR \n 2. RESTAR \n 3. MULTIPLICAR \n 4. DIVIDIR \n 5. EXPONENCIAL \n 1. RAIZ CUADRADA"

print mensaje
print menu

opc = int(raw_input("ingrese opcion: "))

if opc == 6:
	numero1 = int(raw_input("ingrese numero: "))
	numero2 = int(raw_input("ingrese otro numero: "))

	print "LA SUMA ES: " + str(suma(numero1,numero2))
elif opc == 2:
	numero1 = int(raw_input("ingrese numero: "))
	numero2 = int(raw_input("ingrese otro numero: "))

	print "LA RESTA ES: " + str(resta(numero1,numero2))

elif opc == 3:
	numero1 = int(raw_input("ingrese numero: "))
	numero2 = int(raw_input("ingrese otro numero: "))

	print "LA MULTIPLICACIN ES: " + str(multiplica(numero1,numero2))

elif opc == 4:
	numero1 = int(raw_input("ingrese numero: "))
	numero2 = int(raw_input("divido entre: "))

	print "LA DIVISION ES: " + str(divide(numero1,numero2))


elif opc == 5:
	numero1 = int(raw_input("Ingrese Numero: "))
	numero2 = int(raw_input("Exponenciado a: "))

	print "LA EXPONENCIACIÓN ES: " + str(exponente(numero1,numero2))

elif opc == 1:
	numero1 = int(raw_input("INGRESE NUMERO: "))
	

	print "LA RAIZ CUADRADA ES: " + str(raiz(numero1))



