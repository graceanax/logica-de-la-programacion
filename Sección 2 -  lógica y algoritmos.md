## Lógica y algoritmos
### ¿Qué es la lógica?
Permiteme iniciar con el típico ejemplo: ¿Recuerdas que algunas veces al abrocharte la camisa de botones fallaste y te ha quedado torcida? bueno, la solución es desabrocharla e iniciar pensando que cada botón debe pertenece a un ojal, y así logras abrocharte la camisa con éxito.

Veamos otro ejemplo, alguna vez que te mojaste bajo la lluvia y al día siguiente tenías malestar, pensaste: Claro, ayer me mojé, era lógico que hoy amaneciera enfermo.

Así es, todo lo que realizamos tiene lógica detrás, es algo cotidiano, que, aunque realicemos de forma automática, lleva una serie de procedimientos obvios que sabemos que funcionan, o sabemos que toda acción tiene su reacción por lógica.

Definir la lógica sin tomar un diccionario es complejo, pero creo que todos comprendemos el punto. Ahora bien, la lógica de la programación no es distinta, aprenderás una serie de técnicas que te permitirán resolver problemas computacionales de forma “lógica”, tal como abrochar una camisa, con práctica verás que será automático.

### Solucionando problemas de lógica

Para resolver un problema, nuestra primera dificultad es encontrar una solución. Perdón que menciono tantas cosas obvias, pero es importante recordar estos conceptos.

Como sabes pocas veces nos detenemos a entender los detalles del problema, para determinar una serie de pasos que nos pueden llevar a una solución, regularmente todo esto sucede en automático.

Veamos este ejemplo, es tu primer día de clases y te asignan el salón 3-405, por supuesto tu solo conoces la oficina de información y la administración de tu facultad.

Sin temor a equivocarme, la mayoría de las personas intentamos ir por nuestra cuenta a descubrir cuál es la lógica detrás de la numeración de los salones, primero sabes que es un edificio único, por lo tanto, el número 3, puede indicar el nivel del edificio, así que subimos al tercer nivel del edificio, ahora apuntamos nuestra mirada a los primeros salones y nos damos cuenta de que indica 3-401, 3-402, etc.

Felicitaciones nuestra lógica era correcta, tal como vimos al inicio sin darte cuenta estableciste una serie de pasos para resolver este problema y dar con la solución.

Con este ejemplo también quiero resaltar que para resolver cualquier problema debemos tener un objetivo claro, en este caso era llegar al salón 3-405, imagina que no tuvieras el número de salón Sin duda hubieras acudido a la oficina de información a que te lo proporcionaran, así es a que te dieran un objetivo que te permitiera saber, hacia donde vas, y hacia donde debes llegar.

Aunque parece que dije lo mismo, saber a donde vas y a donde debes llegar no es lo mismo, puedes saber a donde te diriges, pero no saber cuándo debes detenerte.

Entonces para poder visualizar bien el camino a seguir para la solución de cualquier problema, debemos tener claro cuál es nuestro objetivo.

Ahora bien, este camino que te comento tiene un nombre, y es el siguiente tema que veremos.

### ¿Qué son los algoritmos?

Es el camino lógico que nos permitirá cumplir nuestro objetivo, por lo tanto, es un conjunto de pasos secuenciales que permiten lograr un objetivo.

Y recordemos que para poder determinar nuestro algoritmo debemos tener muy claro nuestro objetivo.

Para quedar más claro, veamos un ejercicio para adquirir un libro en formato digital (epub), específicamente el libro los 7 hábitos de la gente altamente efectiva.

**Objetivo:** Adquirir el libro "los 7 hábitos de la gente altamente efectiva"

En este caso observemos que lo único que deseamos es adquirir el libro, esto no significa que lo leeremos, ni que vamos a comparar precios debemos tener en mente que solo deseamos adquirirlo.

**Algoritmo:** Ingresamos a Google en nuestro navegador web, realizamos la consulta: comprar libro digital los 7 hábitos de la gente altamente efectiva, ingresamos al primer resultado que nos devuelve la búsqueda, si es un sitio seguro realizamos la compra, si no regresamos a los resultados de la búsqueda y continuamos con el siguiente resultado donde repetimos el proceso.

Pero si nos fijamos esto no pasa de un texto explicativo que nos permitirá lograr nuestro objetivo. En este caso un algoritmo debe ser organizado de una forma más entendible, para poder adquirir cualquier libro digital.

~~~
Algoritmo Adquirir_libro_digital

Inicio
1. Conocer el título del libro a adquirir
2. Ingresar a Google desde nuestro navegador Web
3. Realizar la búsqueda especificando que se desea comprar libro digital
4. Ingresar a un resultado
5. Es un sitio seguro
       Comprar libro digital y detenernos
   No es un sitio seguro
       Regresar al resultado de la búsqueda
       Ir al paso 4
Fin
~~~
Veamos algunas cosas importantes del algoritmo que acabamos de realizar.

- Algunas de las líneas están numeradas
- Cada línea lleva una secuencia, se debe cumplir la primera para poder continuar
- Si realizamos todos los pasos podemos adquirir cualquier libro en formato digital a menos que no exista.
- El algoritmo no es muy detallado, especialmente en el proceso de compra que bien podría ser otro algoritmo.

Un algoritmo debe tener el nivel de detalle suficiente para que no exista confusión a la hora de ejecutarlo.

Algo que es muy importante es que a este tipo de algoritmos se les conoce como informales, ya que no son fácilmente implementados por una computadora, son más reflexiones humanas.

Algo que es muy importante es que todo algoritmo debe ser probado antes de su ejecución, para que tengamos la certeza de lograr el objetivo que nos planteamos, a esta prueba en conceptos técnicos se le llama prueba de escritorio, que sería la simulación de poner en marcha el algoritmo.

## Ejercicio: Algoritmos informales

1. Desarrollar un algoritmo que permita encender una vela
2. Desarrollar un algoritmo que permita tomar una selfie
3. Desarrollar un algoritmo que permita silbar
