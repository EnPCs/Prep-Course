Conceptos:
* Los objetos constituyen otro contenedor de datos.  Los objetos y las matrices son similares en ciertas cosas y muy diferentes en otras.  Mientras los arrays pueden contener múltiples elementos relacionados unos con otros, los objetos contienen mucha información sobre una sola cosa.  Los objetos se instancian usando llaves ( { } ). Un objeto es una colección de propiedades.

* Una propiedad es una asociación entre un nombre (o clave) y un valor. El valor de una propiedad puede ser una función, en cuyo caso la propiedad es conocida como un método. Además de los objetos que están predefinidos en el navegador, puedes definir tus propios objetos.  Una propiedad de un objeto se puede explicar como una variable adjunta al objeto.  Las propiedades de un objeto definen las características del objeto.

* Un método es una función asociada a un objeto, o, simplemente, un método es una propiedad de un objeto que es una función. Los métodos se definen normalmente como una función, con excepción de que tienen que ser asignados como la propiedad de un objeto. 

* Los bucles son una forma rápida y sencilla de hacer algo repetidamente. Hay muchos diferentes tipos de bucles, pero esencialmente, todos hacen lo mismo: repiten una acción varias veces.  Un ciclo for se repite hasta que una condición especificada se evalúe como false.  La instrucción for-in itera sobre todas las propiedades enumerables de un objeto que está codificado por cadenas.

* La notación de puntos solo funciona con nombres de propiedades que son válidos como de identificadores  [Especificaciones] , así que básicamente cualquier nombre que también sea un nombre de variable válido (un válido ¡identificador) y cualquier palabra clave reservada [Especificaciones] .

* La notación de corchetes espera una expresión que se evalúa como una cadena (o puede ser forzada a una cadena), por lo que puede usar cualquier secuencia de caracteres como nombre de propiedad. No hay límites para lo que puede contener una cadena.

Ejemplos:

obj.foo;  // valid
obj.else  // valid, reserved keywords are valid identifier names
obj.42    // invalid, identifier names cannot start with numbers
obj.3foo  // invalid,                ""
obj.foo-bar // invalid, `-` is not allowed in identifier names
obj[42]   // valid, 42 will be coerced to "42"
obj["--"] // valid, any character sequence is allowed
obj[bar]  // valid, will evaluate the variable `bar` and 
          // use its value as property name

