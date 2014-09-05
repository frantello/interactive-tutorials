Tutorial
--------

Java es un lenguage orientado a objetos. Los objetos en Java son creados a partir de plantillas llamadas clases.

Vamos a comenzar por un programa de ejemplo típico, comúnmente conocido como "Hola, Mundo!", al ejecutarlo mostrará por pantalla el texto "Hola, Mundo!".

    public class Main {
        public static void main(String[] args) {
            System.out.println("Hola, Mundo!");
        }
    }

La primera línea define una clase llamanda Main.

    public class Main {

En Java, cada línea de código que necesitamos ejecutar necesita estar dentro de una clase. Esta línea declara una clase llamada `Main`, que es de acceso público, es decir, visible a cualquier otra clase.

Notese que cuando se declara una clase pública, el nombre del fichero debe ser el mismo (Main.java), de otra forma daría un error de compilación.

Cuando escribamos los ejemplos en este sitio no usaremos la palabra reservada public para evitar problemas, ya que sólo usaremos un único fichero para todas las clases.

La siguente línea es:

    public static void main(String[] args) {

Este es el punto de entrada a nuestro programa. El método principal debe tener siempre esta signatura para que Java pueda ejectuarlo.


* `public` significa que todo el mundo puede usarla.
* `static` significa que puedes usar el método sin necesidad de instanciar un objeto `Main`.
* `void` significa que el método no devuelve ningún valor.
* `main` es el nombre del método.

The arguments we get inside the method are the arguments that we will get when running the program with parameters. It's an array of strings. We will use it in our next lesson, so don't worry if you don't understand it all now.

    System.out.println("HOla, Mundo!");

* `System` es una clase predefinida de utilidades que provee el lenguaje.
* `out` is a static variable within System that represents the output of your program (stdout).
* `println` is a method of out that can be used to print a line.

Exercise
--------

Print "Hello, World!" to the console.

Tutorial Code
-------------

public class Main {

    public static void main(String[] args) {

        System.out.println("Adiós, Mundo!");

    }

}

Expected Output
---------------

Hola, Mundo!

Solution
--------
