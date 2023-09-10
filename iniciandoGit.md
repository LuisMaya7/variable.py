# Definir variables de diferentes tipos primitivos
entero = 2023
flotante = 3.14159265359
cadena = "Hola, soy una cadena"
booleano = True

# Concatenar las variables en una cadena (convertir las no cadenas según sea necesario)
resultado_cadena = cadena + " - Entero: " + str(entero) + " - Flotante: " + str(flotante) + " - Booleano: " + str(booleano)

# Imprimir la cadena resultante
print("Cadena resultante:", resultado_cadena)

# Investigación sobre límites de enteros y flotantes
# Los enteros en Python no tienen un límite absoluto, pero dependen de la memoria disponible.
# Para obtener el límite máximo de enteros en tu sistema, puedes usar sys.maxsize.
import sys
limite_enteros = sys.maxsize

# Los flotantes en Python tienen un límite, que se puede consultar con sys.float_info.
import sys
limite_flotantes = sys.float_info.max

print("Límite de enteros:", limite_enteros)
print("Límite de flotantes:", limite_flotantes)

# Calcular la suma de los primeros n números pares
n = 10  # Puedes cambiar el valor de n según tus necesidades
suma_pares = n * (n + 1)  # La fórmula para la suma de los primeros n números pares

# Imprimir la suma de los primeros n números pares
print("Suma de los primeros", n, "números pares:", suma_pares)
# Este código define variables de diferentes tipos, las concatena en una cadena, investiga los límites de enteros y flotantes, y ca los primeros n números pares (donde n es un valor que puedes ajustar según tus necesidades). Luego, imprime los resultados de estas tareas.

