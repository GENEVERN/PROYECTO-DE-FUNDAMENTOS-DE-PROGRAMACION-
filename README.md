# PROYECTO-DE-FUNDAMENTOS-DE-PROGRAMACION-

# Qué es Python?

Python es un lenguaje de programación de alto nivel que se utiliza para desarrollar aplicaciones de todo tipo. A diferencia de otros lenguajes como Java o .NET, se trata de un lenguaje interpretado, es decir, que no es necesario compilarlo para ejecutar las aplicaciones escritas en Python, sino que se ejecutan directamente por el ordenador utilizando un programa denominado interpretador, por lo que no es necesario “traducirlo” a lenguaje máquina

# Qué es una variable?

Una variable es un sitio donde guardamos una determinada información. En función del tipo de información que guardemos (texto, números, booleanas, etc.), la variable será de uno u otro tipo.

## Nombrando una variable

```python
Mari_a = 15
Maria3 = 15
Maria = 15
MariA = 15
_Maria = 15 


No valido 
3Maria = 15
Ma ria = 15
Mar-ia = 15
```

## Asignando valores a una variable

Las variables en Python se crean cuando se definen por primera vez, es decir, cuando se les asigna un valor por primera vez. Para asignar un valor a una variable se utiliza el operador de igualdad (=). A la izquierda de la igualdad se escribe el nombre de la variable y a la derecha el valor que se quiere dar a la variable.
```python
x = 2.5 

Si una variable no se ha definido anteriormente, al escribir su nombre generara un mensaje de error.
```

## Operadores básicos

Existen cinco operadores basicos  tales como suma + , resta - ,multiplicacion *  , divison / , modulo % :

### Suma

El operador  suma + los valores de tipo de datos numéricos.
```python
num1 = 10
num2 = 15

sum= num1 + num2 
print("sum")

respuesta: 25
```

### Resta

El operador resta -  los valores de tipo de datos numéricos.
```python
num1 = 20
num2 = 5

rest= num1 - num2 
print("rest")

respuesta: 15
```
### Multiplicación

El operador  multiplica * los valores de tipo de datos numéricos.
```python
num1 = 4
num2 = 5

mult= num1 - num2 
print("multi")

respuesta: 20
```
### División

El operador división / el resultado que se devuelve es un número real.
```python
num1 = 36
num2 = 4

div= num1 / num2 
print("div")

respuesta: 9
```
### Módulo

El operador módulo % no hace otra cosa que devolver el resto de la división entre los dos operandos.
``` python
num1 = 7
num2 = 2

mod= num1 % num2 
print("mod")

respuesta: 1
```
# Tipos de datos en Python
A continuacion tenemos los siguientes tipos de datos dentro de Python

## Integer
Son un tipo de datos que permite representar números enteros, pueden ser numeros positivos y negativos pero no decimales.
``` python
a = 5  
b = 100  
c = - 3
``` 

## Float

El tipo numérico float permite representar un número positivo o negativo con decimales, es decir, números reales.
``` python
a = 3.89  
b = -6.1  
c = 10.6
``` 
## String

Las cadenas en Python o strings son un tipo inmutable que permite almacenar secuencias de caracteres. Para crear una, es necesario incluir el texto entre comillas dobles ". 
``` python
s =  "Cadena de Maria"
print(s)       
print(type(s)) 
```
También es valido declarar las cadenas con comillas simples simples '.
``` python
s = 'Cadena de Maria'
print(s)        
print(type(s))  
```
## Casting en Python

Hacer un casting significa convertir un tipo de dato a otro. 
Existen dos tipos de conversiones : conversión implícita y conversión explícita.

Conversión implícita: Esta conversión de tipos es realizada automáticamente por Python.
``` python
a = 1   # <class 'int'>
b = 2.3 # <class 'float'>

a = a + b
print(a)       # 3.3
print(type(a)) # <class 'float'>
```


conversión explícita: Podemos hacer conversiones entre tipos o cast de manera explícita haciendo uso de diferentes funciones que nos proporciona Python. Las más usadas son las siguientes: float(), str(), int(), list(), set()

## List

Las listas en Python permiten almacenar un conjunto arbitrario de datos como enteros, cadenas y hasta otras funciones.
``` python
lista = [1,52,maria,2,13]
print(lista)

Resultado [1,52,maria,2,13]
``` 
## Tuple
Las tuplas es un conjunto ordenado en secuencia e inmutable de elementos del mismo o diferente tipo.

``` python
tupla = (1, 2, 3)
print(tupla) #(1, 2, 3)
``` 
``` python
También pueden declararse sin (), separando por , todos sus elementos.
tupla = 1, 2, 3
print(type(tupla)) #<class 'tuple'>
print(tupla)       #(1, 2, 3)

Resutado : 1
           2
           3
``` 

Una tupla puede no contener ningún elemento, es decir, ser una tupla vacía.
``` python
()
>>> len(())
0
``` 
## Dictionary
Un Diccionario es una estructura de datos y un tipo de dato en Python con características especiales que nos permite almacenar cualquier tipo de valor como enteros, cadenas, listas e incluso otras funciones , el cual esta divido en pares llave y valor.
Los diccionarios se pueden crear con paréntesis {} separando con una coma cada par key: value.
``` python
d1 = dict([
      ('Nombre', 'Genesis'),
      ('Edad', 18),
      ('Documento', 0968694729),
])
print(d2)
#{'Nombre': 'Maria', 'Edad': '18', 'Documento': '0968694729'}

``` 
# Tomando decisiones

## Sentencia if
La sentencia if se utiliza para ejecutar un bloque de código si, y solo si, se cumple una determinada condición. Por tanto, if es usado para la toma de decisiones.
``` python
if condición:"aquí van las órdenes que se ejecutan si la condición es cierta y que pueden ocupar varias líneas"
La condición se evalúa siempre y cuando:
-Si el resultado es True se ejecuta el bloque de sentencias
-Si el resultado es False no se ejecuta el bloque de sentencias.
```
``` python
a = 5
if a < 5:
    print('a es menor que 5')
 ```
 
## Sentencia elif
Esta sentencia contiene el código a ejecutar en caso de que no se cumpla la condición de la sentencia if.
``` python
 a= 5
 if a > 10:
   print('a es mayor que 10')
 else:
  print('a es menor o igual que 10')

 a es menor o igual que 10
 ```
## Ciclo For

El bucle for es una iteración que recorre los elementos de una secuencia ordenada como listas, diccionarios, tuplas, cadenas, etc.
``` python
La sintaxis del bucle for en Python es tal que así:
for var in sequence:
    statement(s)
 ```
 La estructura del bucle for es simple. La primera línea identifica el bucle y define un índice, que es un número que cambia en cada paso a través del bucle. Después de la línea de identificación viene el grupo de comandos que se quiere ejecutar de forma IDENTADA.
 ``` python
 grupos = [Exo, Got7, twice, NCT]
for a in grupos:
    print(a)
  ```
## Ciclo While
La sentencia o bucle while en Python es una sentencia de control de flujo que se utiliza para ejecutar un bloque de instrucciones de forma continuada mientras se cumpla una condición determinada.
``` python
La sintaxis del bucle while es la siguiente:

while condicion:
    cuerpo del bucle
 ```   
La ejecución de esta estructura de control while es la siguiente:
``` python
Python evalúa la condición:
-si el resultado es True se ejecuta el cuerpo del bucle. Una vez ejecutado el cuerpo del bucle, se repite el proceso 
(se evalúa de nuevo la condición y, si es cierta, se ejecuta de nuevo el cuerpo del bucle) una y otra vez mientras la condición sea cierta.

-si el resultado es False, el cuerpo del bucle no se ejecuta y continúa la ejecución del resto del programa.
```
``` python
while numero <= 10:
    suma = numero + suma
    numero = numero + 1
print ("La suma es " + str(suma))
```
## Break
La instrucción break  proporciona la oportunidad de cerrar un bucle cuando se activa una condición externa. Debemos poner la instrucción break dentro del bloque de código bajo la instrucción de su bucle, generalmente después de una instrucción if condicional.
``` python
number = 0

for number in range(10):
    if number == 5:
        break    # break here

    print('Number is ' + str(number))

print('Out of loop')
```

## Continue
La instrucción continue da la opción de omitir la parte de un bucle en la que se activa una condición externa, pero continuar para completar el resto del bucle. Es decir, la iteración actual del bucle se interrumpirá, pero el programa volverá a la parte superior del bucle.

La instrucción continue se encuentra dentro del bloque de código abajo de la instrucción del bucle, generalmente después de una instrucción if condicional.
``` python
number = 0

for number in range(10):
    if number == 5:
        continue    # continue here

    print('Number is ' + str(number))

print('Out of loop')
```
