# Curso de Python - Airbus

Instructor: Alan Badillo Salas [badillo.soft@hotmail.com](badillo.soft@hotmail.com)

## 1. Fundamentos

Un programa en `python` consite de variables, funciones, clases y módulos los cuales
mediante estructuras de control nos permiten resolver problemas computacionales.

Es recomendable seguir los siguientes puntos para resolver un problema:

* Plantear el problema de forma que logremos identificar la entrada y salida del programa.

* Idear un método conceptual de como resolveríamos el problema si fueramos una computadora.

* Plantear el algoritmo que soluciona el problema de tal forma que quede como una lista de pasos
que logremos entender y seguir hasta alcanzar la solución y creamos que es posible de implementar.

* Codificar cada uno de los pasos mediante python tomando en cuenta que las repeticiones o ciclos
del algoritmo y las decisiones se llevarán a cabo mediante las estructuras de control
(`for`, `while`, `if`).

### 1.1 Variables

Las variables son espacios de memoria nombrados asociados a un tipo para guardar datos en nuestro
programa, por ejemplo, valores temporales para realizar operaciones o incluso arreglos de datos
para procesarlos.

> Distintos tipos de variables y métodos útiles

~~~py
# declarar una variable que guarde un numero
a = 123

# crear otra variable utilizando el valor de a guardado
b = a ** 2 # x ** y : es el operador exponencial x^y

# imprimir los valores de las variables
print a, b
~~~

Las variables pueden almacenar números enteros, flotantes, cadenas de caracteres, booleanos, nulos,
arreglos de otras variables o valores, tuplas de datos, diccionarios y expresiones lamda.

~~~py
# 1 / 3 devuelve 0 porque la division entre numeros enteros es entera
a = 1 / 3.0
b = 2 / float(a)

# mediante la interpolacion de cadenas podemos dar formato a numeros con decimales
print "A = %.2f | B = %.8f" % (a, b)
~~~

### 1.2 Funciones
