Tutorial
--------

Java es un lenguage orientado a objetos. Los objetos en Java son creados a partir de plantillas llamadas clases.

Vamos a comenzar por un programa de ejemplo típico, comúnmente conocido como "Hola, Mundo!", al ejecutarlo mostrará por pantalla el texto "Hola, Mundo!".

    public class Main {
        public static void main(String[] args) {
            System.out.println("Hola, Mundo!");
        }
    }

La primera línea define una clase llamada Main.

    public class Main {

En Java, cada línea de código para ejecutar necesita estar dentro de una clase. Esta línea declara una clase llamada `Main`, que es de acceso público, es decir, visible a cualquier otra clase.

Notese que cuando se declara una clase pública, el nombre del fichero debe ser el mismo (Main.java), de otra forma daría un error de compilación.

Cuando escribamos los ejemplos en este sitio no usaremos la palabra reservada public para evitar problemas, ya que sólo usaremos un único fichero para todas las clases.

La siguente línea es:

    public static void main(String[] args) {

Este es el punto de entrada a nuestro programa. El método principal debe tener siempre esta signatura para que Java pueda ejectuarlo.


* `public` significa que todo el mundo puede usarla.
* `static` significa que puedes usar el método sin necesidad de instanciar un objeto `Main`.
* `void` significa que el método no devuelve ningún valor.
* `main` es el nombre del método.

Los argumentos definidos en el método se corresponden a los parámetros pasados en la ejecución del programa. Es una tabla de cadenas de texto. Por ahora no te preocupes por esto, lo explicaremos en otra lección.

    System.out.println("HOla, Mundo!");

* `System` es una clase predefinida de utilidades que provee el lenguaje.
* `out` es una variable estática definida en System que representa la salida estandar del programa (stdout).
* `println` es un método que se usa para escribir texto con salto de línea al final.

Exercise
--------

Print "Hola, Mundo!" en la consola.

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
public class Main {

    public static void main(String[] args) {

        System.out.println("Hola, Mundo!");

    }

}
