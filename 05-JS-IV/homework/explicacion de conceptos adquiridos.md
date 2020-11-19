# Homework: Javascript IV

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Objetos
	* Propiedades
	* Métodos
	* Bucle `for…in`
	* Notación de puntos vs notación de corchetes



* Objetos

Los objetos son contenedores de gran cantidad de información, que se ordena ya no por indices como los arreglos, sino por pares lammados clave:valor, o key: value en ingles, donde las claves son unicas dentro de cada objeto, y los valores pueden ser de cualquir tipo de datos como string ,  numeros, boleanos , funciones e incluso objetos,  etc. Los valores pueden repetirse a diferencia de las claves.

* Propiedades

Las propiedaes, según lo visto hasta aqui son las claves , existiendo muchos tipos de propiedades y que se comportan de manera distinta. Pero el concepto es mucho más complejo a medida que profundizamos en el estudio del lenguaje distinguiendose propiedades enumerables y no enumerables, propias y heredadas, de solo lectura o configurables, por convención pueden establecerse como privadas,etc. 

 * Métodos

Los metodos son funciones que pueden establecerse dentro de los objetos. Es decir son parte del codigo escrito dentro de un objeto que se usa reiteradas veces al ser llamados sin tener que reescribirlos cada vez que sea necesario utilizarlo. Hasta aqui hemos visto varios metodos como .pop . push . length que son propios del lenguaje y por ello no son enumerabes porque no pueden recorrerse con un bucle for ... in , que procesa las propiedades propias y heredadas, lo cual no quiere decir que sean menos importantes.    

* Bucle `for…in`

Es un bucle al igual que el for visto hasta aqui pero con caracteristicas distintas, porque en las matrices o arreglos podemos recorrerlos con indices numericos. En el bucle for ...in entre parentesis definimos la palabra clave in y e nombre del objeto que nos permite rrecorrer las claves del objeto finalizando cuando se hallan iterado todas las claves.


 * Notación de puntos vs notación de corchetes

 Hay dos formas de acceder a los valores usando puntos , nombreFuncion.clave o corchetes accediendo a los valores por el nombreFuncion['clave']. La primera llamada  dot notation o notación de punto y la segunda bracket notation o notacion de corchetes. Esta última es la más utilizada porque nos permite utilizar variables que apunten a cadenas o numeros haciendo que el codigo pueda ser escalable.

 

