*EJERCICIO*

Desarrolla una calculadora modular en Python. La lógica de cada operación matemática (suma, resta, multiplicación, etc.) deberá
 implementarse como una función separada en un módulo independiente. Luego, importa esas funciones en un archivo    principal que actúe
como interfaz para el usuario.

Este ejercicio lo debes realizar en pareja utilizando la metodologia gitflow, el aprendiz A crea el repo y debe crear
la rama develop, CADA aprendiz realizara dos funciones,  es decir el aprendiz A crea la rama sobre develop Funcion-A
y en esta rama desarrolla las dos funciones, el Aprendiz B clona el repo abre Develop y crea la rama Funcion-B donde
realizará las demas funciones. Luego el aprendiz B debe enviar un pull request y el aprendiz A debe verificar el
codigo para luego autorizarle a mergear el codigo en Develop, luego el aprendiz A debe enviarme un pull request
para verificar todo el codigo evaluarlo y confimar mediante mensaje que puede mergear el codigo.
Requisitos:
1. Crea un módulo (por ejemplo, operaciones.py) que contenga una función para cada una de las siguientes operaciones:
 
Suma
 
Resta
 
Multiplicación
 
División (/)
 
Potencia (**)
 
División entera (//)
 
2. En el archivo principal (por ejemplo, calculadora.py):
 
Solicita al usuario dos números y un operador.
 
Utiliza estructuras de control (if/elif/else) para determinar qué función importar y ejecutar desde el módulo operaciones.
 
Muestra el resultado de manera clara.
 
Incluye manejo de excepciones para:
 
Divisiones por cero
 
Entradas no numéricas
 
Operadores inválidos
 