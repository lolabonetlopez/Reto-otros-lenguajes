*Nombres de los integrantes*: Lola Bonet y Raul Ferris
*Lenguaje*: Java
*Reto asignado*: Bucles


Preguntas de investigación y comparación

1. ¿Cómo se declara la variable o el contador?
En Java hay que indicar explícitamente el tipo: int i = 1. Java es un lenguaje de tipado estático, así que el compilador necesita saber que i es un entero antes de usarlo. Python, al ser de tipado dinámico, no requiere esta declaración (i = 1 basta).

2. ¿Cómo se muestra información por consola?
Con System.out.println(i). System.out es el flujo de salida estándar, y println imprime el valor y salta de línea. Equivale al print() de Python.

3. ¿Cómo se delimitan los bloques de código? Comparación con Python.
En Java los bloques se delimitan con llaves { }. En Python, en cambio, la indentación es la sintaxis: define el bloque y un error de indentación es un error de sintaxis. Además, cada instrucción en Java termina en ;, algo que Python no exige.

4. ¿Qué símbolos o palabras cambian respecto al ejemplo en Python?
En cuanto a símbolos y palabras, for i in range(1, 6): se convierte en for (int i = 1; i <= 5; i++) {, añadiendo el tipo int para declarar el contador y sustituyendo la función range() por una condición explícita (i <= 5) y un incremento explícito (i++). El print(i) de Python pasa a ser System.out.println(i);. Además, en Java aparecen las llaves { } para delimitar el bloque (en lugar de la indentación) y el punto y coma ; al final de cada instrucción, ninguno de los cuales existe en Python.

5. ¿Qué decisiones o repeticiones se mantienen? Algoritmo en castellano (sin código).
La lógica es idéntica en ambos lenguajes: se parte de un valor inicial (1), se repite una acción (mostrar el valor actual) y, tras cada repetición, se incrementa el valor en uno; el proceso se detiene en cuanto el valor supera el límite establecido (5). Es decir, "empezar en 1, mientras el número no sea mayor que 5, mostrarlo por pantalla y pasar al siguiente". La estructura de control (inicio, condición, avance) es la misma; lo único que cambia es la sintaxis con la que cada lenguaje la expresa.

6. ¿Elementos adicionales necesarios para ejecutar el programa?
Sí, en Java, al ser compilado y orientado a objetos, exige que todo código ejecutable esté dentro de una clase, y que exista un método main con la firma exacta public static void main(String[] args), que es el punto de entrada que la JVM busca al ejecutar el programa. Esto es ajeno a la lógica del bucle en sí (Python puede ejecutar un for suelto en un script sin necesidad de ninguna función envolvente).