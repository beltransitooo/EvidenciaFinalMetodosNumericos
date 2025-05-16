# Método de Biseccion

Este proyecto implementa el **Método de Bisección** en Java para encontrar raíces de funciones no lineales. Se utiliza una función predefinida \( f(x) = x^3 - x - 2 \) y se permite al usuario ingresar un intervalo \([a, b]\), una tolerancia, y un número máximo de iteraciones.

## Lenguaje

Java

## Cómo usar

Ingresa los datos solicitados en la terminal:

Límite inferior a

Límite superior b

Tolerancia deseada (ej. 0.0001)

Número máximo de iteraciones

El programa mostrará una tabla con los valores de cada iteración y la aproximación final de la raíz.

## Verificaciones y calculos

Verificar que f(a) y f(b) tengan signos opuestos.

Calcular el punto medio c = (a + b)/2.

Evaluar f(c) y reemplazar uno de los extremos según el signo.

Repetir el proceso hasta cumplir la tolerancia deseada o alcanzar el número máximo de iteraciones.

Este método es útil para encontrar raíces de funciones continuas en intervalos cerrados donde se cumple el teorema de Bolzano.

## Autor

[Angel Miguel Beltran Zazueta]

## Profesor

[@BryanVazquezHdez](https://github.com/BryanVazquezHdez)
