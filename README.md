# Recursion en funciones lambda
---
En este caso calcularemos el factorial de un número usando expresiones lambda y recursividad.
---
Partimos de la expresion lambda:

``` python
lambda x: 1 if x == 0  λ(x)
```
Aprovechamos la orientacion a objetos de python definiendo:
```python
fact = lambda x: 1 if x == 0 else x * fact(x-1)
```
Generando un llamado recursivo, reduciendo el valor del parametro x, hasta 0 y obtener lo que se requiere evaluando:
```python
fact(n)
```
Siendo n el número al cual se obtiene el correspondiente factorial
