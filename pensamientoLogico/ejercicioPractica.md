# Reloj 

 Para elaborar un algoritmo de un reloj, necesitarás conocer lo siguiente: las variables que tendrás a tu disposición y cuál es el problema a resolver.

 ## Qué variables necesita el algoritmo.

  El tiempo está conformado principalmente por las siguientes variables:


 - segundos: la unidad mínima de este problema. Lo representaremos por la letra S mayúscula.
 - minutos: un minuto está conformado por 60 segundos. Lo representaremos por la letra M mayúscula.
 - horas: una hora está conformada por 60 minutos. Lo representaremos por la letra H mayúscula.

Después de definir nuestras variables, deberemos establecer un punto de partida, esto depende del problema, en este caso será cuando inicia un día. Por consiguiente, el momento que exista 0 horas, 0 minutos y 0 segundos (00:00:00) será el punto inicial.

Una vez definido el punto de partida, deberemos establecer un punto de llegada, esto depende del problema, en este caso será cuando termine un día. Por consiguiente, el momento que exista 23 horas, 59 minutos y 59 segundos (23:59:59) será el punto final.

## Cómo elaborar el diagrama de flujo del algoritmo.

Para crear el diagrama de flujo para el algoritmo de un reloj sigue estos pasos:

1)  Define el Inicio del algoritmo en una figura ovalada.
2) Inicializa las variables. En este caso las horas, minutos y segundos en 0.
3)  Mostrar las variables.
4) Reasignar la variable segundos, con el valor actual de segundos más una unidad: S = S + 1.
 Esto debes controlarlo cuando los segundos lleguen a un valor de 60.
5) Preguntar: ¿la variable segundos es igual a 60?.

   1)   En caso de que la respuesta sea No, vamos a volver al paso 3 y seguir con el flujo.
   2) En caso de que la respuesta sea Sí, vamos a reiniciar segundos a 0 y reasignamos el valor actual de minutos más una unidad: M = M + 1. Esto último debemos controlarlo cuando los minutos lleguen a un valor de. 

6) Preguntar: ¿la variable minutos es igual a 60?.
    1) En caso de que la respuesta sea No, vamos a volver al paso 3 y seguir con el flujo. Como esta línea de flujo ya existe, entonces nos conectamos a esa línea de flujo, mostrando la fecha a esa conexión, sin sobreponerla.
    2) En caso de que la respuesta sea Sí, vamos a reiniciar minutos a 0 y reasignamos el valor actual de horas más una unidad: H = H + 1. Esto último debemos controlarlo cuando las horas lleguen a un valor de 24.

7) Preguntar: ¿la variable horas es igual a 24?.

    1) En caso de que la respuesta sea No, vamos a volver al paso 3 y seguir con el flujo. Como esta línea de flujo ya existe, entonces nos conectamos a esa línea de flujo, mostrando la fecha a esa conexión, sin sobreponerla.
    2)  En caso de que la respuesta sea Sí, vamos a reiniciar las horas a 0.


## Desafío del algoritmo de un reloj.

El diagrama de flujo del algoritmo de un reloj está inconcluso, por lo tanto, tu trabajo será terminarlo. Existen dos alternativas:

- Crear un final al algoritmo después de llegar al punto final
- Volver a conectarlo en algún proceso para que el reloj funcione correctamente.





