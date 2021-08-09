# Homework: Javascript II

****************
El concepto FOR.
****************
Se utiliza para implenmentar los denominados bucles de operaciones.
Viene dado por la palabra reservada for luego las condiciones de ejecución y los codigos de operación:

for(declaración de variable e inicialización; opción a evaluar; ajuste de variable para parada o stop del bucle)

for (var i = 0; opcion a evaluar de variable i; i++){
    código
}

Este for ejecutará el código mientras la "opcion a evaluar sea verdadera".


**************************************
Los operadores lógicos `&&`, `||`, `!`
**************************************
El operador && equivale a AND (Y), el cual permite evaluar que una condición y otra (u otras) deben cumplirse. Por ejemplo:

if (opcion1 && opcion2){
    código
}
Para que el código sea ejecutado DEBEN cumplirse ambas opciones (opcion1 y opcion2), sino, no se ejecutará.


El operador || equivale a OR (O), el cual permite evaluar que alguna de las condiciones debe cumplirse. Por ejemplo:

if (opcion1 && opcion2){
    código
}
Para que el código sea ejecutado DEBE cumplirse al menos una de las opciones (opcion1 ó opcion2), sino, no se ejecutará.


El operador ! equivale a NOT (NO o NEGACION), el cual también permite evaluar que alguna de las condiciones debe cumplirse. Por ejemplo:

if (!opcion1 && opcion2){
    código
}
Para que el código sea ejecutado DEBE cumplirse no opcion1 ó opcion2, sino, no se ejecutará.
Otro ejemplo:
if (!false){
    codigo
}
Acá se ejecutrá solo si es verdadero (true) ya que es false negado.

