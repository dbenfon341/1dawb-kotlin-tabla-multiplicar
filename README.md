# 1dawb-tabla-multiplicar

LA TABLA DE MULTIPLICAR

En la entrega, adjunta la URL a tu repositorio.

Crea un nuevo proyecto, copia y pega el siguiente código en el fichero Main.kt:

/**
 * Solicita un número entero en un rango.
 *
 * @param min Int - valor mínimo
 * @param max Int - valor máximo
 *
 * @return Int - número entero válido dentro del rango especificado
 */
fun pedirNum

/**
 * Realiza una pregunta para contestar con s/si ó n/no
 *
 * @param text String - Texto de la pregunta
 *
 * @return Boolean - true/false dependiendo de la respuesta válida a la pregunta
 */
fun pregunta

fun main() {
    //TODO: Solicitar la introducción de un número entre 1 y 100 y mostrar su table de multiplicar...
    //Hasta que se responda negativamente a la pregunta "¿Desea generar otra tabla de multiplicación? (s/n)"
}
Para crear la tabla de multiplicar utiliza el constructor Array() cómo se indica en los apuntes...

https://revilofe.github.io/section1/u04/teoria/PROG-U4.1.-kotlin/#arrays

Ejemplo de los apuntes:

val allCards = Array(12, { i -> i + 1 })
println("${allCards.first()} - ${allCards.last()}") // => 1 - 12
En nuestro caso, debemos crear un array de 10 posiciones con el contenido que puedes observar en los pantallazos de ejemplo de funcionamiento del programa ya resuelto y se muestra a continuación... utiliza un bucle for para recorrer y mostrar el contenido del array con el resultado.

Esto es lo que debe mostrar la aplicación:

![Imagen 1](https://i.imgur.com/QrOYDbU.png)

Ejemplo de ejecución del programa Tablas de Multiplicar...

Si se genera un error, debe controlarse... por ejemplo:

Numero no valido

O si se introduce una respuesta que no se entiende:

Error en respuesta

En cualquier caso, después de mostrar el error debe permanecer esperando a que pulsemos la tecla ENTER para continuar...
