### Valores: cadenas y números
## Introduccción
En una computadora solo existen datos, los cuales se pueden leer, modificar y crear. Los datos son guardados en largas secuencias de bits.

Los bits son cualquier cosa con dos valores, normalmente podemos conocerlos como un 0 y 1, dentro de nuestra computadora esto representa formas como alta o baja carga eléctrica, como también puede ser un punto brillante u opaco como la superficie de un CD.  

Por ejemplo, veamos como representar el número 14 en bits. Funciona igual que los números decimales, solo que en vez de tener 10 dígitos solo tenemos 2, y el peso de casa uno se incrementa po un factor de 2 de derecha a izquierda. Por ejemplo para representar el número 14.

|128|64|32|16|8|4|2|1|
|-|-|-|-|-|-|-|-|
|0|0|0|0|1|1|1|0

Así que ese es el número binario que representa el 14 = 00001110, que es 8+4+2

## valores
Imagina ver un cielo lleno de bits, una computadora moderna típica tiene más de 30 mil millones de bits en su almacenamiento de datos volátil (memoria RAM). El no volátil tiene aún más.

Para que podamos trabajar con tantos bits sin perdernos, podemos agruparlos en trozos que representen piezas de información, en este caso estos trozos los llamamos valores.

Como podemos darnos cuenta más adelante cada valor tiene un tipo que nos ayudará a determinar su rol. Concluyamos entonces que un valor esta representado por una serie de bits.

// averiguar lo de los datos

Ahora veamos lo que mencionamos anteriomente, cada valor tiene un tipo y esto determinará su rol, veamos entonces
 tipos de valores simples y operaciones que podemos realizar con ellos.

### Números
No es ninguna sopresa que los valores de este tipo esten representados por números, veamos un ejemplo:

~~~
22
~~~

Tal cual si utilizamos este número **22** en un programa, causará que el patrón de bits para el número 13 exista dentro de la memoria de la computadora.

Algo que me gustaría aclarar es que en el caso de los números decimales hacemos uso de **"."** para delimitar la parte entera de su fracción

~~~
7.34
~~~

#### Operadores aritméticos
Con estas operaciones podemos realizar lo principal que realizamos con la arimética (suma, resta, multiplicación y división).

únicamente que para realizar estas operaciónes utilizaremos los siguiente operadores aritméticos.

|Operación|Operador|
|--|--|
|Suma|+|
|Resta|-|
|Multiplicación|*|
|División|/|
|Módulo|%|

¿Te has fijado en el último operador? Es posible que no lo reconozcas, el operador aritmético llamado **modulo** podemos obtener el *sobrante* de una división, por ejemplo:

Dividir **10/2** rel resultado sería **5** y siendo 2 divisible entre 10, obtendremos 0 como sobrante, por lo tanto podemos representar el modulo de la siguiente forma:

~~~
10%2
=> 0
~~~

Nos tenemos que dar cuenta también de la precedencia de los operadores, en este caso, la suma y resta tienen la misma precedencia, la multiplicación, división y módulo tienen la misma precedencia, por lo tanto si realizamos la siguiente operación:
~~~
1+4*6
~~~
La multiplicación se realizará primero, pero en el caso que exista operciones con símbolos de la misma precedencia, se aplican los operadores de izquierda a derecha.

De igula forma puedes romper la precedencia de operadores utilizando parentecis, como el siguiente ejemplo:

~~~
(1+2) * 1
~~~
En este caso primero se realizará la operación dentro de los parentesis, esto es bueno, si tienes dudas puedes usar parentecis para evitar problemas de precedencia.

### Cadenas
Este tipo de dato es utilizado para representar texto. Para utilizarlas es necesario limitar su contenido entre comillas dobles o bien simples, siempre y cuando el tipo de comilla coicida  al principio y final.

~~~
"Hola, soy una cadena"
'Hola, soy una cadena'
~~~

La unidad mínima de una cadena -una letra, o símbolo- la llamamos **caracter** por lo tanto, una serie de **caracteres** es una **cadena**.

~~~
Somos Caracteres = "a", "x", "?"
Somos Cadenas = "Hola", "Lógica de la programación"
~~~
**Nota:** algo que debemos tomar en cuenta, es que en una cadena de texto, no podemos dar saltos de linea (Enter) como acostumbramos para dividir un párrafo.

¿Entonces cómo podemos hacer si deseamos escribir un texto con párrafos?

Tenemos una solución llamada **caracteres de escape** es una notación que hace uso de la diagonal invertida (backslash: **\** ) más el caracter **n**, entonces **\n** se interpreta como una nueva línea en nuestra cadena.

Ejemplo:
~~~
"Esta es la primera línea \nY esta es la segunda"
~~~
Por supuesto en este texto no verás el verdadero comportamiento, te invito a que hagamos la prueba en el navegador.

Te invito a que investigues otros caracteres de escape, para las cadenas.

Regresando un poco al tema anterior, no sé si te preguntaste ¿Qué sucede si yo dentro de mi cadena deseo agregar un trozo de texto entre comillas?.

Para eso tenemos una elegante solución, permiteme te la muestro.

~~~
'Dice mi papá, "La ley aplica para todos"'.
~~~
Exacto, por eso es excelente poder usar ambos tipos de comillas para agregar cadenas.

### Concatenación
En el caso de las cadenas, no podemos realizar operaciones aritméticas con ellas como en el caso de los números, pero el caracter **+** nos permite **concatenarlas** que no es lo mismo que sumar, en este caso *pega* dos cadenas, creando una sola. Por ejemplo:

~~~
"con"+"ca"+"te"+"na"
=> "concatena"
~~~

Así es, nos ha devuelto una sola cadena de caracteres, veremos más adelante que esta posibilidad es muy útil.
