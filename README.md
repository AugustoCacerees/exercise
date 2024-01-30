# Tarea de Ejercicios - Test de ingreso a Adhoc para Desarrollador 

Esta tarea consiste en implementar varias funciones que manipulan una lista de personas representadas como tuplas. Cada tupla contiene información sobre una persona, incluyendo su DNI, nombre, apellido y edad.

## Funciones Implementadas

### 1. `ordenar(lista_personas)`

Esta función devuelve una lista con las edades ordenadas de menor a mayor.

### 2. `convertir_a_diccionario(lista_personas)`

Crea un diccionario donde las claves son los números de DNI y los valores son tuplas que contienen nombre, apellido y edad de la persona.

### 3. `devolver_edad(lista_personas, dni)`

Para la lista de personas dada, devuelve la edad de la persona con el DNI especificado. Utiliza el método `convertir_a_diccionario` para hacer la búsqueda más eficiente.

### 4. `eliminar_repetidos(lista_personas)`

Devuelve una lista con elementos únicos eliminando duplicados.

### 5. `separar_por_edad(lista_personas)`

Devuelve dos listas:
- Lista 1: personas mayores de 25 años (inclusive).
- Lista 2: personas menores de 25 años.

### 6. `obtener_promedio(lista)`

Calcula el promedio de una lista de números. Captura la excepción de dividir por cero si la lista está vacía.

## Ejecución

El script también incluye una función `main()` para probar las funciones implementadas. Al ejecutar el script, se mostrarán los resultados de cada función.
