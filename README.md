import math

# Definir las variables
n = 11  # Número de lados del polígono (en este caso, un hendecágono)
l = 5   # Longitud de un lado (puedes cambiar este valor)

# Calcular el área utilizando la fórmula
area = (n * l**2) / (4 * math.tan(math.pi / n))

# Imprimir el resultado
print("El área del polígono de", n, "lados es:", area)
