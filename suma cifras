# Función para sumar las cifras de un número
def suma_cifras(numero):
    suma = 0
    numero_str = str(numero)
    for cifra in numero_str:
        suma += int(cifra)
    return suma

# Pedir al usuario un número de varias cifras
numero = input("Introduce un número de varias cifras: ")

# Verificar si la entrada es un número válido
if numero.isdigit():
    numero = int(numero)
    resultado = suma_cifras(numero)
    print(f"La suma de las cifras del número {numero} es: {resultado}")
else:
    print("Por favor, introduce un número válido.")
