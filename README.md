
# Reto_4
## En este repositorio podrás encontrar los siguientes programas escritos en python.


1. Determina si un número corresponde al codigo ASCII de una vocal minúcula
2. Determina sí el codigo ASCII del primer carácter de una cadena es par o no.
3. Determina sí el carácter es un digito.
4. Determina si un número es positivo, negativo ó igual a cero.
5. Determina sí un punto esta dentro de una circuferencia.
6. Determina sí se puede formar un triángulo dadas tres longitudes positivas.

Entrando al siguiente link encontrarás un notebook para interactuar con el codigo.
[Notebook Reto 4 - Google Colab](https://colab.research.google.com/drive/1HnXGPyUOIt2aOLMIXvkA7Hv-R3_ukxxr?usp=sharing)

## 1). Determina si un número corresponde al codigo ASCII de una vocal minúcula
```python
#VARIABLES
n : int
n = int(input("Escribe un Número entero: "))


#CODE
if n == 97 or n == 101 or n == 105 or n == 111 or n == 117 :
    print( n, ", Representa una vocal minúscula: ", chr(n), " en codigo ASCII" )

else:
    print(n,",no representa una vocal minuscula en codigo ASCII")
     
```

## 2). Determina sí el codigo ASCII del primer carácter de una cadena es par o no.
```python
#VARIABLES
n : str
n = str(input("Escribe un carácter cualquiera: "))

#CODE

if  ord(n[0]) % 2 == 0:

    print("El carácter: ", n[0], " Representa un número par en codigo ASCII")

else:
    print("El carácter: ", n[0], " NO representa un número par en codigo ASCII")
```
## 3). Determina sí el carácter es un digito.
```python
#VARIABLES
n : str
n = str(input("Escribe un carácter cualquiera: "))


#CODE

if  ord(n[0]) >= 48 and ord(n[0]) <= 57:

    print("El carácter: ", n[0], " Representa un didito en codigo ASCII")

else:
    print("El carácter: ", n[0], " NO representa un digito par en codigo ASCII")
```

## 4). Determina si un número es positivo, negativo ó igual a cero.
```python
#VARIABLES
n : int
n = int(input("Escribe un Número natual: "))

#CODE
 
if n > 0:
   print("El número: ",f'\'{n}\'', " es Positivo" )
elif n == 0:
    print("El número: ",f'\'{n}\'', " es el neutro para la suma" )
elif n < 0:
    print("El número: ",f'\'{n}\'', ", es negativo" )
```
## 5). Determina sí un punto esta dentro de una circuferencia.
```python

#* VARIABLES

# Distancia del centro de la circuferencia y la coordenada del punto.
d : int = 0

# Radio de la circuferencia
r = int(input("Escribe el radio de la circuferencia: "))    

# Coordenadas del centro de la circuferencia
# k = a la corrdenada x ; h = a la coordenda y
h : float = float(input("Escribe la coordenada x, de la circuferencia: "))
k : float = float(input("Escribe la coordenada y, de la circuferencia: "))

# Coordenadas del punto
x : float = float(input("Escribe la coordenada x, del punto: "))
y : float = float(input("Escribe la coordenada y, del punto: "))


#* CODE

# Fórmula: calculo de la distancia entre dos puntos,forma euclidiana
# Sí la distancia es menor al radio, el punto esta dentro de la circuferencia.
d = (((x-h)**2)+((y-k)**2))**0.5

if d <= r:
    print("El punto esta dentro de la circuferencia")
else:
    print("El punto NO se encuntra dentro de la circuferencia")
```
## 6). Determina sí se puede formar un triángulo dadas tres longitudes positivas.
```python

#VARIABLES
edge_a : float = float(input("Longitud del lado a: ")) 
edge_b : float = float(input("Longitud del lado b: ")) 
edge_c : float = float(input("Longitud del lado c: "))

t : bool = True


#CODE

# se suman dos lados y se compara con el tercero 
# En caso de que la suma sea inferior, el triángulo no se puede formar

t = edge_a + edge_b > edge_c 

if t == True:
    edge_a + edge_c > edge_b

    if t == True:
        t = edge_b + edge_c > edge_a 

        if t == True:
            print("Se puede formar un triangulo con los lados proporcionados")
        else:
            print("No se puede formar un triangulo con las medidas dadas")

else:
    print("No se puede formar un triangulo con las medidas dadas")
```

Entrando al siguiente link encontrarás un notebook para interactuar con el codigo.
[Notebook Reto 4 - Google Colab](https://colab.research.google.com/drive/1HnXGPyUOIt2aOLMIXvkA7Hv-R3_ukxxr?usp=sharing)

GRACIAS POR SU VISITA

