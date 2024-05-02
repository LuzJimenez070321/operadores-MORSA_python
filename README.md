### OPERADORES MORSA_PYTHON
La versión 3.8 de Python vino con una nueva característica, que algunos programadores de Python anhelaban desde hace bastante tiempo. Se ha introducido una nueva forma de asignar objetos a variables, es decir, el operador :=. Brinda a los programadores una forma conveniente de asignar variables en medio de expresiones. Si miras a los caracteres con un poco de imaginación puedes ver una similitud con los ojos y colmillos de una morsa, por eso cariñosamente se le conoce como el operador morsa (the walrus operator) .
## EJEMPLO 
```python 
if (x := 10 + 5) > 10:
    print(x)  # Devuelve 15
```