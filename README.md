# Ejercicios de programación

El objetivo de realizar estos ejercicios es familiarizarse con los fundamentos del lenguaje de programación que se esté ocupando para resolverlos. Además, en algunos casos permitirán comparar la solución, de un mismo problema, en distintos lenguajes y paradigmas.

Se alienta alienta al lector a compartir sus soluciones con el autor del problemario.

## Tabla de contenidos

* [1 Entrada y salida I](#1-entrada-y-salida-i)
  * [1.1 Conceptos básicos](#11-conceptos-básicos)
  * [1.2 Problemas](#12-problemas)
* [2 Entrada y salida II](#2-entrada-y-salida-ii)
  * [2.1 Conceptos básicos](#21-conceptos-básicos)
  * [2.2 Problemas](#22-problemas)

## 1 Entrada y salida I

[ [Índice](#tabla-de-contenidos) ]

Estos problemas permiten experimentar con las entradas y salidas de un programa regular.

### 1.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **Entrada por parámetros:** como cuando se ejecuta *ping 8.8.8.8*, en donde *ping* es el nombre del programa y *8.8.8.8* es el argumento que se le pasa (la entrada).

* **Salida del programa:** algunos lenguajes de programación, como C y C++, permiten especificar un código que indica si el programa se ejecutó correctamente. Para las soluciones de este problemario, el código siempre debe ser el número cero (0).

* **Salida estándar:** así como la entrada estándar, algunos lenguajes de programación permiten escribir datos en el flujo de salida que provee el sistema operativo. Procuraremos utilizar las instrucciones más básicas del lenguaje de programación, es decir, aquellas que permiten mostrar mensajes en la cónsola de comandos.

### 1.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

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

## 2 Entrada y salida II

[ [Índice](#tabla-de-contenidos) ]

Los siguientes problemas permiten jugar con la entrada estándar de los programas, así como profundizar un poco más en el uso de la salida estándar.

### 2.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **Entrada estándar:** a diferencia de los parámetros, la entrada estándar solo se puede poner en funcionamiento *después* de que empieza la ejecución del programa, es decir, hay que indicarle al programa qué leer y cuándo leerlo. Es útil cuando los datos que debe procesar el programa no están listos antes de que arranque.

### 2.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

1. Escriba un programa que lea un número entero desde su entrada estándar, le sume otro número aleatorio (por ejemplo, -16) y muestre el resultado en la salida estándar.

    Ejemplo:

    * **Entrada estándar:** se le solicitó un número X al usuario, y este último introdujo 10.

    * **Salida:** *Buenas noches. El resultado de sumar 10 + (-16) = -6*

    * **Razonamiento:** en esta modalidad, se suele esperar a que el usuario ingrese los datos de entrada *durante* la ejecución del programa. El usuario introdujo 10. Luego de leer dichos datos, computamos los datos (sumar -16 a la entrada del usuario) y ponemos los resultados en la salida estándar.

2. Escriba un programa que lea un número entero *x* desde su primer argumento y otro número entero *y* desde la entrada estándar, y muestre el resultado de las siguientes operaciones en la salida estándar:

    * x + y - 5
    * y - x * y
    * y \* y \* x
    * -x + (Resto de dividir y entre -4)

    Ejemplo:

    * **Primer argumento que ingresó el usuario:** -7 (x = -7)

    * **Número que introdujo usuario mediante entrada estándar:** 10 (y = 10)

    * **Salida:**

        * (-7) + (10) - 5 = **-2**

        * (10) - (-7) * (10) = **80**

        * (10) \* (10) \* (-7) = **-700**

        * -(-7) + (Resto de dividir (10) entre -4) = **9**

3. Realice una aplicación que lea un número entero *x* y algún texto desde su entrada estándar, saque el resto del número leído entre 8 (x % 8), y muestre el resultado de concatenar (unir) ambos, el número y el texto, mediante un espacio.

    Por ejemplo:

    * **Entrada:**

        * 15

        * animales salvajes

    * **Salida:** 7 animales salvajes

    * **Razonamiento:** *15* y *animales salvajes* es lo que introdujo el usuario. A ese 15 se le saca el resto entre 8, lo que resulta en 7 y dicho resultado se concatena con *animales salvajes*, dejando un espacio entre el 7 y el texto.

4. Programe una aplicación que reciba, primeramente, un caracter y luego solicite al usuario dos oraciones. Luego, la aplicación deberá mostrar ambas oraciones pero rodeadas por el caracter que escogió el usuario.

    Por ejemplo:

    * **Entrada:**

        * **El caracter:** &

        * **Oración 1:** El agua deberia ser transparente cuando no esta sucia

        * **Oración 2:** mantequisha

    * **Salida:**

        * &El agua deberia ser transparente cuando no esta sucia&

        * &mantequisha&

    * **Nota:** es recomendable poner cada oración en una línea diferente.

5. Escriba un aplicativo que lea dos oraciones desde sus primeros dos argumentos, así como otra pero desde la entrada estándar y escriba, en la salida estándar, la segunda oración, la tercera oración y, finalmente, la primera oración, en ese mismo orden y separadas por el caracter \t.

    Ejemplo:

    * **Entrada:**

        * **Argumento 1:** asterisco

        * **Argumento 2:** Por favor, cierre la puerta al salir.

        * **Entrada estándar 1:** de nada

    * **Salida:** Por favor, cierre la puerta al salir.&emsp;de nada&emsp;asterisco

    * **Nota:** así como \n, el caracter \t (TAB) tiene un efecto especial en algunas terminales de comandos. Dichos caracteres son sustituidos por espacios en blanco, cuyo tamaño el sistema operativo decide. Es el equivalente a presionar la tecla TAB en procesadores de palabra como Word.

6. Escriba un programa que lea dos caracteres *c1* y *c2*, además de dos números enteros *i1* e *i2*, todos desde la entrada estándar y por separado. Luego, mostrar dichos valores usando la siguiente fórmula:

    i2c1c2c2i2i1

    **Nota:** sustituir c1, c2, i1 e i2 por los valores leídos.

    Por ejemplo:

    * **Entrada:**

        * E

        * n

        * 58

        * -9

    * **Salida:** -9Enn-958

7. Escriba una aplicación que reciba dos números enteros *n* y *m* mediante los argumentos de programa y que lea un caracter *c* desde la entrada estándar. En su salida estándar, el aplicativo deberá mostrar lo siguiente:

    1. El caracter *c* tal y como fue leído desde la entrada

    2. El caracter *c* pero en mayúscula

    3. El caracter *c* pero en minúscula

    4. El caracter que esté *n* caracteres después del caracter *c*

    5. El caracter que esté *m* caracteres antes del caracter *c*

    Ejemplo:

    * **Entrada por argumentos:** 2 4

        En ese caso, n = 2 y m = 4.

    * **Entrada estándar:** f

    * **Salida:**

        1. f

        2. F

        3. f

        4. h

        5. b

    * **Razonamiento:**

        1. *f* es el caracter tal y como se leyó desde la entrada estándar.

        2. *F* es el caracter que se leyó pero en mayúscula.

        3. *f* es el caracter que se leyó pero en minúscula. Nótese que transformar un caracter que ya está en minúscula resulta en el mismo caracter. De cualquier forma, siempre se debe aplicar la transformación.

        4. *h*. Como *n = 2*, se calculó el segundo caracter después de *f*, que corresponde a *h*.

            | f | g | *h* | i | j |
            |---|---|---|---|---|
            | 0 | 1 | **2** | 3 | 4 |

        5. *b*. Como *m = 4*, se calculó el cuarto caracter que precede a *f*, que corresponde a *b*.

            | a | *b* | c | d | e | f |
            |---|---|---|---|---|---|
            | 5 | **4** | 3 | 2 | 1 | 0 |

    * **Pista:** para conseguir el caracter antes o después de otro caracter *c*, se le puede sumar o restar, en el código, a ese *c* la cantidad de posiciones en la que se desee desplazar. Por ejemplo, para el caracter *H*, tres posiciones atrás es *H - 3 = E*. Para ese mismo caracter, dos posiciones hacia adelante es *H + 2 = J*.

8. Realice una aplicación que lea una oración desde su entrada estándar y la muestre en la salida dos veces: la primera con el segundo caracter de la oración en mayúscula y la segunda línea con el tercer caracter de la oración en minúscula.

    Por ejemplo:

    * **Entrada:** tres tristes tigres comieron trigo en un trigal

    * **Salida:**

        * t**R**es tristes tigres comieron trigo en un trigal

        * tr**e**s tristes tigres comieron trigo en un trigal

     Segundo ejemplo:

    * **Entrada:** BaNDEjas

    * **Salida:**

        * B**A**NDEjas

        * Ba**n**DEjas

9. Escriba un programa que reciba una oración mediante su primer argumento y un número entero *n* a través de su entrada estándar, para que luego muestre la oración leída pero con el caracter en la posición *n* transformado en un espacio en blanco.

    Ejemplo:

    * **Entrada por argumentos:** "salidA"

    * **Entrada estándar:** 2

    * **Salida:** sa idA

    * **Razonamiento:** como *n = 2*, se modifica el caracter en la posición 2 de la oración.

        | s | a | *l* | i | d | A |
        |---|---|---|---|---|---|
        | 0 | 1 | **2** | 3 | 4 | 5 |

        **Resultado:**

        | s | a |  | i | d | A |
        |---|---|---|---|---|---|
        | 0 | 1 | **2** | 3 | 4 | 5 |

    * **Consejo:** investigar como modificar un caracter en un valor de tipo char*. Los char* son *cadenas de caracteres* (character *strings*).

10. Realice un programa que reciba un número entero *n* a través de su primer argumento y una oración mediante su entrada estándar, para que luego muestre la oración leída pero con el caracter en la posición *n* transformado en un asterisco.

    Ejemplo:

    * **Entrada por argumentos:** 2

    * **Entrada estándar:** "la par"

    * **Salida:** la*par

    * **Razonamiento:** como *n = 2*, se modifica el caracter en la posición 2 de la oración.

        | l | a |   | p | a | r |
        |---|---|---|---|---|---|
        | 0 | 1 | **2** | 3 | 4 | 5 |

        **Resultado:**

        | l | a | * | p | a | r |
        |---|---|---|---|---|---|
        | 0 | 1 | **2** | 3 | 4 | 5 |

    * **Consejo:** investigar las maneras de leer una cadena de caracteres mediante las funciones de entrada estándar. Luego buscar cómo modificar un caracter específico de dicha cadena.
