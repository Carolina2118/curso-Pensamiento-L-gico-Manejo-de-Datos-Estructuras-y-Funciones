
Las estructuras de control permiten tomar decisiones y realizar un proceso repetidas veces. Se trata de estructuras muy importantes, ya que son las encargadas de controlar el flujo de un programa.

Condicionales: Permiten tomar decisiones a partir de una comparación u operación.

Ciclos: Realizan diferentes iteraciones de acuerdo a condiciones o situaciones que pide el algoritmo.
Estructuras dentro de cada grupo:
-------------------------------------------------------------------------
Condicionales                                ciclos

if / else                                    For
Switch                                       While                                 
Try / catch                                  Do-While.
-------------------------------------------------------------------------

Los condicionales son estructuras de control que te permiten evaluar diferentes expresiones como verdadero o falso y realizar determinadas acciones.

   ## Cómo utilizar un condicional if-else.

 - Un condicional if evalúa una expresión si es verdadera. La palabra reservada else evalúa cuando la expresión del if es falsa, pero no es obligatorio colocarlo.

![Captura de pantalla de 2023-03-22 17-13-16](https://user-images.githubusercontent.com/67702555/227028763-42208fa3-4338-48bf-9579-94cda97d12c1.png)


 - En otras palabras, si (if) una acción (expresión) es verdadera (true) realizo una acción (bloques de código), caso contrario (else) realizo otra acción.

    ## Cómo utilizar el condicional switch.

 - La estructura switch es otra forma de evaluar condiciones, la diferencia con if es que las condiciones deben ser iguales a un caso o valor en específico.
 
 
 - Colocamos la palabra reservada switch y seguido de la variable o expresión a evaluar. Después   colocamos cada caso con la palabra reservada case y el valor   que deberá ser igual a la expresión. Seguido colocamos el bloque de código a ejecutar.

 - Finalmente, colocamos la condición por defecto con la palabra reservada default que se ejecutará si ninguno de los casos fue el correcto. Esto es semejante al bloque else.

![Captura de pantalla de 2023-03-22 17-15-43](https://user-images.githubusercontent.com/67702555/227029513-4b2d95aa-1873-4401-95ed-41aadcabf7f5.png)


 - Esto se leería de la siguiente manera: evalúa (switch) la variable expresion, en el caso de que sea igual a uno (case 1), entonces ejecuta el bloque 1 y termina, en el caso de que sea igual a dos (case 2), entonces ejecuta el bloque 2 y termina, si no se cumple ninguna, ejecuta un bloque por defecto (default).
    Ejemplo utilizando switch

 - Por ejemplo, creemos un semáforo, dependiendo del valor de la variable color, se evaluará un determinado bloque de código.
![Captura de pantalla de 2023-03-22 17-16-41](https://user-images.githubusercontent.com/67702555/227029593-c97d6034-208f-497d-86ee-b6e4bac61af0.png)


