

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `prototype`
* _Constructors_ (de Clases)


* `prototype`

Como hemos visto en JS todos son objetos, que pueden tener propiedades enumerables, y pueden tener funciones del prototipo del que derivan, no enumerables.

Por ejemplo un array tiene una unica propiedad enumerable que es el indice, pero tiene ademas muchas propiedades qeu derivan de su prototipo. Esto es porque hereda de su prototipo propiedades y metodos
ej:

array.length que es una propiedad que pertenece al objeto array y no la construimos nosotros sino que deriva de del prorotipo array y tiene un metodo que nos devuelve la longitud del array.

Otros ejemplos de metodos o funciones definidas en el prototipo array son:

Array.pop()
Array.push()
Array.unshif()
Array.shift()
Array.slice(comienzo, cantidad)
Array.prototype.concat()
Array.prototype.copyWithin()
Array.prototype.entries()
Array.prototype.every()
Array.prototype.fill()
Array.prototype.filter()
Array.prototype.find()
Array.prototype.findIndex()
Array.prototype.flat() 
etc.

Cada una de estas funciones devuelven una propiedad que no definimos nosotros pero estan en el prototipo.
Cuando invocamos una propiedad el compilador busca en el objeto definido por nosotros y si no lo encuentra busca en su prototipo, y si no lo encuenta busca en el prototipo anterios si existe hasta llegar a objet, si no lo encuentra, nos devuelve error.

* _Constructors_ (de Clases)

Las mal llamadas Clases en JS, o al menos discutidas, son plantillas que nos premiten crear objetos iguales cuyas propiedades pueden contener cualquier valor o incluso funciones , objetos anidados, array, etc.

Estos constructores nos permiten evitar errores al crear objetos, si los realizamos con el contructor y no de forma literal, pero además y lo más importante que nos permite compartir metodos o funciones sin volver a crearlos en cada objeto lo que permite un ahorro muy importante de recursos como la memoria.

