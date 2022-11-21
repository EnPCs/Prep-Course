
1 Archivo de texto explicando conceptos
	Crear el archivo de texto, para ello en consola de Visual Code studio:
		touch nombre del archivo.txt
		touch 02-js-2actividadReadme.txt
	Abrir el nuevo archivo creado con un editor de texto
		gedit 02-js-2actividad Readme.txt
	Resolver los conceptos planteados en el punto 1, guardar y salir del archivo respectivo.

		for, Es un bucle utilizado para repetir una o más instrucciones un determinado número de veces. FOR se suele utilizar cuando sabemos el número de veces que queremos que se ejecute. La sintaxis del bucle for se muestra a continuación.

		El bucle FOR tiene tres partes incluidas entre los paréntesis, que nos sirven para definir cómo deseamos que se realicen las repeticiones. La primera parte es la inicialización, que se ejecuta solamente al comenzar la primera iteración del bucle. En esta parte se suele colocar la variable que utilizaremos para llevar la cuenta de las veces que se ejecuta el bucle.

		La segunda parte es la condición, que se evaluará cada vez que comience una iteración del bucle. Contiene una expresión para decidir cuándo se ha de detener el bucle, o mejor dicho, la condición que se debe cumplir para que continúe la ejecución del bucle.

		Por último tenemos la actualización, que sirve para indicar los cambios que queramos ejecutar en las variables cada vez que termina la iteración del bucle, antes de comprobar si se debe seguir ejecutando.

		Después del for se colocan las sentencias que queremos que se ejecuten en cada iteración, acotadas entre llaves.
		Un ejemplo de utilización de este bucle lo podemos ver a continuación, donde se imprimirán los números del 0 al 10.

>var i 
 for (i=0;i<=10;i++) { 
   	document.write(i)
   	document.write("<br>") 
 }

0
1
2
3
4
5
6
7
8
9
10

		&&, operador lógico empleado como si fuera un "y". Es decir, en la condición de la sentencia IF, se puede añadir este operador para que en vez de una sola condición, se cumplan 2 o más condiciones.
 
		Entonces, para que se ejecuten las instrucciones del IF, se tienen que cumplir todas las condiciones que escribamos con el operador &&. 
 
		Ejemplo en el cual se tienen que cumplir 2 condiciones. Introduciremos 2 números, y ambos tienen que ser mayor que 5, sino, no se cumplirá la condición:

var num1;
var num2 ;
num1 = prompt('Introduce un numero: ' ,'') ;
num2 = prompt('Introduce otro numero: ' ,'');
if (num1 > 5 && num2 > 5)
{
document.write('Ambos numeros son mayor que 5');
}
else
{
document.write('Alguno de los dos numeros no es mayor que 5'):
}

		||, operador lógico que permite que el IF se ejecute en caso de que UNA de las dos condiciones (cualquiera) o las dos se cumplan. Es decir, que con que se cumpla alguna de las condiciones que hemos programado, ya se ejecuta el IF, no hace falta que se cumplan todas. 
 
		Aquí el ejemplo:

var num1;
var num2 ;
num1 = prompt('Introduce un numero: ' ,'') ;
num2 = prompt('Introduce otro numero: ' ,'');
if (num1 > 5 || num2 > 5)
{
document.write('Ambos numeros son mayor que 5');
}
else
{
document.write('Alguno de los dos numeros no es mayor que 5'):
}

		!,  permite convertir una variable en booleana para evaluación en una declaración if.  En pocas palabras: !variable significa tomar el valor de verdad de variable y negarlo.

		Por lo tanto, if (!variable) { ingresará la cláusula if si la variable es false (o coacciona a falso)

if (!variable.onsubmit || (variable.onsubmit() !=false))

		Significa: verifique si variable.onsubmit está definido y es verdadero (por lo tanto, verdadero), luego verifica si llamar a onsubmit devuelve un resultado que coacciona a verdadero. En una línea corta, comprueba si no hay onsubmit o devuelve verdadero.

