# ¿Qué es un dato?.

- Es una porción de información muy concreta y especifica que nos permite, a través de diferentes operaciones y estructuras, tomar decisiones. Hacen parte de un algoritmo en una estructura más grande.
Son la base sobre la cual partimos y sobre la cual llegamos, además, componen todas las estructuras para que puedan funcionar y sean operables.

## Tipo de datos texto:

- El tipo de dato texto consiste en un conjuntos de caracteres. Los caracteres pueden ser letras, números, símbolos, espacios e incluso emojis. A estos datos también se los denominan como cadena de caracteres (strings).

### "los espacios tambien son una cadena de caracteres"

- Los tipos de datos de texto, también llamados “strings”, o “cadenas de texto”, son un tipo de datos compuesto por unidades mínimas, conocidas como “caracteres”, los cuales incluyen letras, espacios, números, y símbolos, todos estos tipos de caracteres pueden encontrarse simultáneamente en un mismo string de texto, como se ve a continuación:

"¿Ana tiene 21 años?"

letras = ["a", "n", "t", "i", "e", "ñ", "o", "s"]
símbolos = ["¿", "?"]
números = ["21"]

Una cadena de texto puede hacer o no sentido semántico; es decir, un string de texto también puede ser un código aleatorio o sin significado semántico.
En un contexto en el que los string de texto se encuentran combinados con otros tipos de datos, el string suele ser diferenciado y separado por medio de comillas, como indicado en el ejemplo anterior.
 
 ## Cómo utilizar los tipos de datos texto.

- En lenguajes como JavaScript, Python o C++, a las cadenas de caracteres se representan entre comillas dobles ( ") o simples ().   

  Ejemplos de estos son:

    "Este es un texto"
    "Ana compró 20 frutas"
    "¡Nunca pares de aprender! 💚"

  Fíjate que todo lo que se encuentra entre las comillas, son los caracteres que conforman el texto, inclusive los espacios, signos de puntuación, números o emojis.

  Los espacios, signos o números también son caracteres, porque al momento de definir que un dato es de tipo texto, entonces cada uno de sus elementos serán los caracteres. Esto debes tener claro para no cometer errores en la manipulación de cadenas de texto.

## Qué es la concatenación.

- Qué es la concatenación

 La concatenación consiste en la unión de cadena de caracteres. Por lo que ambos bloques deben ser del mismo tipo de dato, en este caso de tipo texto.

 Por ejemplo, analiza el siguiente ejemplo de concatenación, ¿cuál crees que sería el resultado?

"Ana" + "está" + "feliz"

 La respuesta es "Anaestáfeliz", todo unido, porque estamos uniendo cadenas de caracteres. Si quisieras que haya espacios, deberás concatenar espacios.

 "Ana" + " " + "está" + " " + "feliz"
