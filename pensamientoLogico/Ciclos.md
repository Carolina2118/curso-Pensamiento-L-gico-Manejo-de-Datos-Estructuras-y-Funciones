![Captura de pantalla de 2023-04-03 19-08-05](https://user-images.githubusercontent.com/67702555/229646833-899c776f-1d9c-4cd9-b87f-d027c3fd4d3a.png)
Un bucle (loop) o ciclo repetitivo es una estructura de control que te permite realizar una o varias instrucciones mientras una condición sea verdadera.

Todo bucle necesita un valor inicial y un incremento. El incremento es necesario para que no exista un ciclo infinito.

Existen tres tipos de ciclos repetitivos:

   - For (para)
   - While (mientras)
    - Do-while (haz algo mientras)

## Qué es un ciclo for

Para el ciclo for conocemos la cantidad de veces que la estructura repetirá una o varias instrucciones.

Por ejemplo, si queremos los 10 primeros números, sabemos que el ciclo se repetirá 10 veces. Si accedemos a los elementos de un array, sabemos que el ciclo se repetirá n veces, donde n es la longitud del array.
Cómo utilizar el ciclo for

La estructura del ciclo for es la siguiente:

for (inicio; comparación; incremento)
    "Bloque de código"
La condición consta de tres partes:

   - Inicio: se debe inicializar una variable que será evaluada en la expresión a comparar.
   - Comparación: es una expresión que debe cumplir la variable inicial, cuando no se cumpla, el ciclo termina.   Esta parte es la que determina el número de   veces que se efectúa el bucle.
   - Incremento: son los intervalos que cambiará la variable inicial, mientras cumpla con la expresión de comparación.

Esto se leería de la siguiente manera: “para (for) un inicio, que cumpla la comparación en determinados incrementos, realiza un bloque código. Si no está dentro del rango, termina el ciclo”.

## Qué es un ciclo while

Para el ciclo while no conocemos la cantidad de veces que la estructura repetirá una o varias instrucciones. Aunque también se puede acoplar para que realice un determinado número de repeticiones.

Por ejemplo, si queremos que un usuario ingrese un valor mayor a 0, no sabremos cuántas veces se equivocará. También, si queremos que un programa se ejecute hasta que el usuario ingrese una opción para salir.

## Cómo utilizar el ciclo while.

La estructura del ciclo while es la siguiente:

while (condición) 
    "Bloque de código"
    "Cambiar la condición para salir del bucle"
    
    En este caso la condición es una expresión lógica a evaluar, si es verdadero repite el bloque de código, si es falso el ciclo termina. Debido a esto, necesitas cambiar la variable de la condición, para que no existe un bucle infinito.

Esto se leería de la siguiente manera: “mientras (while) cumpla una condición, realiza una serie de instrucciones. Incrementa o cambia la condición para volverla a evaluar, si al cambiar la condición es falsa, sale del bucle”.


## Qué es un ciclo do-while.

Un ciclo do-while sigue la misma tendencia que un while, la diferencia está en que do-while ejecuta el bloque de código una vez y después evalúa la condición. Si la condición es verdadera, vuelve a repetir el código.

do
    "Bloque de código"
    "Cambiar la condición para salir del bucle"
while (condición).

Esto se leería de la siguiente manera: “realiza (do) una serie de instrucciones, mientras (while) cumpla una condición, vuelve a realizarlas. Incrementa o cambia la condición para evaluar la condición, si la condición es falsa, sale del bucle”.

## Algoritmo de generación de números con el ciclo for.

El algoritmo consiste en generar los números del 1 al 10, utilizamos un bucle for porque conocemos el número de ciclos para resolver el problema.

Para realizar un bucle for necesitaremos lo siguiente:

   - Inicio: inicializamos una variable con el valor de 1, generalmente se utiliza i (índice) como variable para el bucle, pero no es obligatorio. En este caso utilizaremos num.
   - Condición: la condición será mientras sea menor o igual que 10 (num <= 10),
   - Pasos: debemos aumentar la variable en una unidad, por lo tanto, podemos utilizar num = num +1.

## La estructura es la siguiente:

  for (num = 1; num <= 10; num = num + 1) 
     Mostrar num


    Esto se leería como: "Para (for) la variable num que inicia en 1 (num = 1) mientras sea menor o igual que 10 (num <= 10) en pasos de 1 (num = num + 1) muestra la variable num".

     Mira la siguiente tabla que muestra cómo cambia la variable num en cada ciclo.

    






