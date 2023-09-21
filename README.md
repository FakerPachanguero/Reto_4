
# Reto_4
- En este repositorio podrás encontrar los siguientes programas escritos en python.
Entrando al siguiente link encontrarás un notebook para interactuar con el codigo.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2FFakerPachanguero%2FReto_4/main?labpath=nb_Repo_4.ipynb)

1. Determina si un número corresponde al codigo ASCII de una vocal minúcula
2. Determina sí el codigo ASCII del primer carácter de una cadena es par o no.
3. Determina sí el carácter es un digito.
4. Determina si un número es positivo, negativo ó igual a cero.
5. Determina sí un punto esta dentro de una circuferencia.
6. Determina sí se puede formar un triángulo dadas tres longitudes positivas.

## 1). Determina si un número corresponde al codigo ASCII de una vocal minúcula
```python
  
n : int
n = int(input("Escribe un Número Entero: "))

if n >= 97 and n <= 122:
    print( n, ", Representa la letra minúscula: ", chr(n), " en codigo ASCII" )

else:
    print(n,",no es una letra minuscula en codigo ASCII")
     
```

## 2). Determina sí el codigo ASCII del primer carácter de una cadena es par o no.
```python
n : str
n = str(input("Escribe un carácter cualquiera: "))


if  ord(n[0]) % 2 == 0:

    print("El carácter: ", n[0], " Representa un número par en codigo ASCII")

else:
    print("El carácter: ", n[0], " NO representa un número par en codigo ASCII")
```
## 3). Determina sí el carácter es un digito.

## 4). Determina si un número es positivo, negativo ó igual a cero.
## 5). Determina sí un punto esta dentro de una circuferencia.
## 6). Determina sí se puede formar un triángulo dadas tres longitudes positivas.




