1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Variables
	* Strings
	* Funciones (argumentos, `return`)
	* Declaraciones `if`
	* Valores booleanos (`true`, `false`)

CONCEPTOS
Variables: Son espacios de memoria donde se almacena información y podemos dirigirnos a ella de acuerdo al nombre de la misma.

Para definir variables en JS se necesita declararlas a través de las siguientes palabras revesrvadas:  
var
let
const

Ejemplo: var nombreVariable = valor;
Declarar una variable tipo string: var miString = "Mi String o cadena de caracteres";
Declarar una variable numérica = var = miNumero = 9;
Declarar una variable booleana = var = false,

STRINGS
Existen dfirentes tipos de datos que podemos almacenar dentro de las variables, como pueden ser:
Strings, numeros y boleanos

Strings deben ir encerradas entre comillas (simples o dobles) y determinan que el dato es una cadena de carcatres o string
Los numeros iran tal cual, ejem var x = 9;
Las booleanas var variable = true;

FUNCIONES.
Son partes de código o rutinas determinadas, invocables desde cualquier parte de nuestro programa general.
A ellas se les pueden pasar atributos, que serán los datos que procesará dicha función, donde al terminar el procesamiento, devolverá la ejecución a aquel punto desde donde se invocó.

Pueden declararse de la siguiente manera:
 function (argumento1, argumento2,...){
     código
     return resultado
 }

 IF.
 Las instrucciones IF, se refieren a condicionales,. donde se evalúa alguna condición para procesar la información contenida en ella.
 Por ejemplo:

 If (condición){
     código
 }

 Pueden ir anidadas, donde utilizaremos la estructura if () else, evaluando así varias opciones dependientes:

 if (condicion){
     código1
 } else {
     código2
 }