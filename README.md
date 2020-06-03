# Recursion en funciones lambda
---
Partimos de la expresion lambda:

``` python
lambda x: 1 if x == 0  λ(x)
```
Aprovechamos la orientacion a objetos de python definiendo:
```python
fact = lambda x: 1 if x == 0 else x * fact(x-1)
```
Generando un llamado recursivo, reduciendo el valor de x hasta 0
