# Programaci-n-B-sica
PYTHON 
> python es un lenguaje de programacion actualmete en el hambito de la tecnologia,Python fue creado por Guardor van Rossum a principio de los años 90, cuyo nombre fue inspirado en el grupo de comicos ingleses Monty Python es un lenguaje similar a c+, pero con una sintacxis muy limpia y que favorese un codigo legible ".


----
## comando
> Generar una salida con asistencia **(Print)**

>La entrada del usuario en el teclado usado **(raw_input)**

Realizar calculos sencillos 

* suma **+**

* resta **-**

* multiplicacion ** * **

* division** / o //**

* modulo ** %**

* potencia  *


----
## Anaconda 

1. para entar a nuestro directorio escribir **dir**
2. para entrar a la terminal escribir el comando **(Python)**.
3. Para entrar a una carpeta escribir el comando **(cd espacio despues el nombre de la capeta)**.

4. para ejecutar un programa ir a donde esta el programa escribir **(python espacio el nombre del programa)**

5. para salir de python usamos **exit()**


existen dos formas de ejecutar codigo en python , la cual puede ser mediante una seccion ,interactiva (linea a linea) con el interprete o bien de la forma abitual, escribiendo el codigo en un archivo de codigo fuente como bloc de notas o spieder 

----
## print()

>print es un comando que permite al usuario mostrar el texto en pantalla,el texto que queremos mostrar se escribe como argumento y encerrado en comillas ** " "**

>donde print es = comando

> mi_cadena= argumento


    mi_cadena= "tengo hambre y faltan 60 min para salir"
    
    print(mi_cadena) = tengo hambre y faltan 60 min para salir 

    tengo hambre y faltan 60 min para salir


-----
##float

>Float es un comando que  permite al usuario insertar numeros decimales o enteros en un programa y este nos dara el numero que necesitamos de un programa este es insertado con parentesis y comillas('')

>donde float es = comando 

l = float(input('Inserte el largo de su habitacion: '))
an = float(input('Inserte el ancho de su habitacion: '))
a = l*an
print('El area de su cuarto es: ', a + 'metros cuadrados')


----
##Input

>La funcion input permite al usuario insertar diferentes tipos de datos desde la entrada del programa.


p= float (input('inserte el numero de botellas de 1L o menos: '))
b= float (input('inserte el numeros de botellas demas de 1L: '))
r= p + b *2.5
print('su pago por resiclar es:', r ,'pesos')


---
##def
>def es un comando que permite al usuario utilizarlo antes de una intruccion al programa para darle el valor de un suma, resta o multiplicación.

def sumar(number1, number2=20):
    print number1 # 15
    print number2 # 10
    print number1 + number2

sumar(number2=10, number1=15)


----
##if-elif-else

>if es una costrucion que permite al usuario usarla en el programa para saber si es 'sierto' lo que esta pidiendo en el programa.

>else es una contrucion que permite al usuario saber si en su programa al ejecutarlo saber si  'falso'

humanos=float(input('Indique los anos humanos :'))
perros1=((humanos-2)*(4))+21
perros2=humanos*10.5
if humanos > 2:
    print('la conversion de anos humanos a perros es de ',perros1)
elif humanos < 0:
    print('favor de ingresar los datos de forma correcta')
else: 
    print('la conversion de anos humanos a perros es de ',perros2)


----
##While
>whie es un bucle que permite al usuario ejecutar un grupo de intrucciones en el mismo programa mientras tenga el valor de True.

edad= 0
while edad <19:
    print('Tienes', edad)
    edad= edad+1

print('fin de programa')


---
##for
>for es un bucle que se utiliza como una forma generica de iterar con una sola secuenciaes decir reconocer una secuencia.

print("Comienzo")
for i in [0, 1, 2]:
    print("Hola ", end="")
print()
print("Final")

----
##range 

> range se utiliza en python como una funcion que ayuda al usuario a establecer listas inmutables de numeros enteros en sucesi[on aritmetica, los valores para esta funcion
\se insertan mediante corchetes [].


>>> x = range(10)
>>> x
range(0, 10)
>>> list(x)
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
>>> range(7)
range(0, 7)
>>> list(range(7))
[0, 1, 2, 3, 4, 5, 6]


-----
##turtle

>turtle es un modulo en python que ayuda al usurio a trabajar con graficos en la programacion utilizando el eje X y Y asi con el ancho y largo de la pantalla
con este modulo se pueden oyentar objetosya ya que tambien turtle es un modelo grafico con el cual se puede utilizar para realizar diversas animaciones.

import turtle

def dibujar (tur,d,s):
    for i in range(1):
        tur.forward(100)
        tur.left(45)
        
     
     
ventana=turtle.Screen()
ventana.bgcolor('lightgreen')
ventana.title('funciones')

alex=turtle.Turtle()
alex.pensize(3)
alex.color('blue')




for i in range(8): 
    dibujar(alex,8,100)
    
    
    
ventana.mainloop()
