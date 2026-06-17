# mungob

# Programa para calcular el promedio de una lista de números

def calcular_promedio(lista_numeros):
    if len(lista_numeros) == 0:
        return 0
    return sum(lista_numeros) / len(lista_numeros)

# Ejemplo de uso
numeros = [10, 8, 9, 7, 6]
promedio = calcular_promedio(numeros)

print("Los números son:", numeros)
print("El promedio es:", promedio)


