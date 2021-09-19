# Ejercicios de programación

El objetivo de realizar estos ejercicios es familiarizarse con los fundamentos del lenguaje de programación que se esté ocupando para resolverlos. Además, en algunos casos permitirán comparar la solución, de un mismo problema, en distintos lenguajes y paradigmas.

Se alienta alienta al lector a compartir sus soluciones con el autor del problemario.

## Tabla de contenidos

* [Entrada y salida I](#entrada-y-salida-i)
  * [Conceptos básicos](#conceptos-básicos)
  * [Problemas](#problemas)

## Entrada y salida I

Estos problemas permiten experimentar con las entradas y salidas de un programa regular.

### Conceptos básicos

* **Entrada por parámetros:** como cuando se ejecuta *ping 8.8.8.8*, en donde *ping* es el nombre del programa y *8.8.8.8* es el argumento que se le pasa (la entrada).

* **Salida del programa:** algunos lenguajes de programación, como C y C++, permiten especificar un código que indica si el programa se ejecutó correctamente. Para las soluciones de este problemario, el código siempre debe ser el número cero (0).

* **Salida estándar:** así como la entrada estándar, algunos lenguajes de programación permiten escribir datos en el flujo de salida que provee el sistema operativo. Procuraremos utilizar las instrucciones más básicas del lenguaje de programación, es decir, aquellas que permiten mostrar mensajes en la cónsola de comandos.

### Problemas

1. Haga un programa que escriba *Hello, world!* en la salida estándar del sistema.

2. Realice un programa que escriba el número *3.141592* en la salida estándar. Procurar que solo aparezcan seis decimales.

3. Realice un programa que escriba el número *2.72* en la salida estándar. Procurar que no aparezcan ceros a la derecha de los decimales.

4. Escriba una aplicación que lea el primer argumento de su entrada y lo escriba en la salida estándar. El primer argumento es la primera palabra que se escribe después del nombre del programa al ejecutarlo.

    Por ejemplo, en la invocación *mi-programa **palabra1** palabra2 3.14*, *mi-programa* es el nombre del programa, mientras que *palabra1* es el primer argumento. *palabra2* y *3.14* son los argumentos 2 y 3 respectivamente.

5. Escriba un programa que lea su primer argumento y le sume un número de su preferencia. Por ejemplo, asumiendo que haya elegido -9 como número de preferencia:

    * **Entrada:** mi-programa 100

    * **Salida:** 91

    * **Razonamiento:** Dado que la palabra escrita después del nombre del programa es *100*, ese será el primer argumento que leerá. Internamente debe sumarle, a ese primer argumento, el número -9 [ 100 + (-9) ] y el resultado se pone en la salida estándar.

6. Escriba un programa que lea su primer argumento, como número entero, y escriba el resultado de las siguientes operaciones separados por espacios:

    * Incrementar en uno (1) el número leído
    * Decrementar en uno (1) el número leído

    Ejemplo:

    * **Entrada:** mi-programa 24

    * **Salida:** 25 23

    * **Razonamiento:** 25 es el incremento por 1 del número 24, mientras que 23 es el decremento por uno de dicho número.

7. Construya una aplicación que lea su primer argumento como un número entero y escriba en la salida estándar, el resto de la división de dicho número entre 7.

    Ejemplo:

    * **Entrada:** mi-programa 18

    * **Salida:** 4

    * **Razonamiento:** el resto de dividir 18 entre 7 es 4.

    * **Consejo:** emplear el operador módulo.

8. Escriba un programa que lea sus primeros dos argumentos (que deben ser números decimales), los sume y escriba el resultado de la suma en la salida estándar.

9. Escriba un programa que lea sus primeros dos argumentos como números decimales y devuelva, mediante la salida estándar la suma, la resta y la multiplicación de dichos argumentos. Los resultados deben estar separados por espacios.

    Por ejemplo:

    * **Entrada:** mi-programa -3 7.1

    * **Salida:** 4.1 -10.1 -21.3

    * **Razonamiento:** 4 es la suma ( -3 + 7.1 ), -10.1 es la resta ( -3 - 7.1 ) y -21.3 es la multiplicación ( -3 x 7.1 ).

10. Escriba un programa que lea sus primeros tres argumentos como palabras (cadenas de caracteres) y las muestre en el mismo orden en la salida estándar, pero sin espacios.

    Por ejemplo:

    * **Entrada:** mi-programa hola como estas

    * **Salida:** holacomoestas

    * **Razonamiento:** los tres argumentos del programa son:

        1. hola

        2. como

        3. estas

        Lo que hace el programa es leer las palabras y luego concatenarlas (pegarlas). Al leerlas no se encontrarán espacios, así que se pueden pegar tal y como se leen.
