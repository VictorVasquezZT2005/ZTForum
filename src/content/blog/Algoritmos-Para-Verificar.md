---
author: Victor Vasquez
pubDatetime: 2024-03-14T20:50:00Z
modDatetime: 2024-03-14T20:50:00Z
title: Algoritmos Para Verificar
slug: Algoritmos-Para-Verificar
featured: true
draft: false
tags:
  - Algoritmos
  - Numeros
  - VictorVasquezZT2005
description: Algoritmos para verificar si un numero es negativo o positivo
---
<strong>Codigo:</strong> Python
```
def check_number(number):
  """
  This function checks if a number is negative, positive, or zero.

  Args:
      number: The number to be checked.

  Returns:
      A string indicating if the number is negative, positive, or zero.
  """

  if number < 0:
    return "El número es negativo."
  elif number > 0:
    return "El número es positivo."
  else:
    return "El número es cero."

# Get user input
number = float(input("Ingrese un número: "))

# Check the number and print the result
result = check_number(number)
print(result)
```
<strong>Probar el Codigo en Linea</strong><br>
<a href="https://programiz.pro/ide/python/PS25VBMFU9?utm_source=python_playground-shared-project-link">Algoritmos Para Verificar</a>

<strong>Creditos</strong>
- <a href="https://t.me/VictorZT2005">@VictorZT2005</a>