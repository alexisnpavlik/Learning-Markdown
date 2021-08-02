Podemos generar textos de distintos tamaños como en html
# Esto en un H1
## Esto es un H2
### Esto es un H3
#### Esto es un H4
##### Esto es un H5
###### Esto es un H6   

Decoradores en el texto como:
 
*italic*  o _italic_  
**negrita** o __negrita__  
_**Combinacion de ambos**_  
~~tachado~~

Listas desordenadas 

* item 1
* item 2
    * item 2.1

Listas ordenadas

1. item 1
1. item 2
    1. item 2.1
1. item 3

Insertar imagenes locales

![github logo](./Github.jpg "comentario")

Insertar imagenes desde la web

![github](https://www.muylinux.com/wp-content/uploads/2017/06/github.png)

Referenciar links

http://github.com o 
[GitHub](http://github.com)

Creamos citas

> "Me gustan las hamburguesas" - Alexis Medina

Creamos comentarios

<!--esto es un comentario-->

Generar un separador
___ 


Escribir codigo

`print("hello word")`

Si posee varias lineas

``` 
def saludar():
    print("Holla")
```

Si queremos que se marque los colores

``` python
Elijo la numero:
    while True:
        if eleccion=="1":
            print("\nIngresa los valores")
            precio_compra=int(input("Cual es el precio de compra: "))
            precio_venta=int(input("Cual es el precio de venta: "))
            usdt=int(input("Cantidad de USDT invertidos: "))
            gancia=((usdt/precio_compra)*precio_venta)-usdt
```

Tambien podemos generar tablas

 Comida |  Precio
------------ | -------------
Hamburguesas | $300
Milanesas | $250

Esta seccion solo sera visible en Github

Lista de tareas  

* [x] tarea 1
* [ ] tarea 2 (no compretada)
    * [x] Subtarea

Mencion a algun usuario  
@alexisnpavlik

Colocacion de emojis 
:worried:


