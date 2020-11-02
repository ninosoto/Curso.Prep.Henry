# Homework: Javascript III

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Arrays



Nota: al ejecutar npm install me devuelve el siguiente error

$ npm install
npm WARN saveError ENOENT: no such file or directory, open 'C:\Users\Usuario\package.json'
npm WARN enoent ENOENT: no such file or directory, open 'C:\Users\Usuario\package.json'
npm WARN Usuario No description
npm WARN Usuario No repository field.
npm WARN Usuario No README data
npm WARN Usuario No license field.

up to date in 1.135s
found 0 vulnerabilities

al ejecutar npm --version me devuelve 

$ npm --version
6.14.8

Creo esta instalado pero no se si falta parte

Otra dificultad es que no se que consola usan en los videos y si hay que descargarlas, por el momento he usado la consola de chrome pero es poco agil manejarse en ella.


Conceptos Adquiridos

Arrays: al igual que en la mayoria de los lenguajes de programación en Javasript tambien tenemos los arrays tambien llamados arreglos o vectores o matrices que nos permiten ordenar datos en variables vinculadas por un indice, teniendo Javasript al igual que en temas anteriores una gran flexibilidad. Como ejemplo podria decirse que son como los vagones de un tren en donde en cada vagon podemos guardar cualquier tipo de datos, incluso indefinidos o nulos, y se ordenan por un numero de orden o indice.

Se definen por medio de una variable explicitamente al poner la expresión [] . 
Podemos declararlos escribiendo los componentes o definiros vacíos y luego ir asignando valores.

Otra gran diferencia es que podemos definir valores dejando en el medio valores indefinidos, cosa que no permiten otros lenguajes

Vimos dos funciones particulares que son push() y Pop() que nos permiten asignar valores con diferencias entre ellas importantes .

.Pusch() adiciona un elemento al final del array incrementando su longitud en 1.
.Pop() elimina el ultimo elemento del array diminuyendo su longitud en 1

Tambien se tiene dos funciones

.unshift() y .shift() que son similares al .Pusch() y .Pop() pero trabajan sobre el primer elemento de la matriz añadiendo o suprimiendo en uno la longitud del array. En ambos casos dado que trabajan sobre el primer elemento modifican la totalidad de los indices de los vagones aumentadolos en uno o diminuyendolos en uno.
