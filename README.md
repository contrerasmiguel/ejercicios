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
* [3 Intercambio de valores](#3-intercambio-de-valores)
  * [3.1 Conceptos básicos](#31-conceptos-básicos)
  * [3.2 Problemas](#32-problemas)
* [4 Operaciones con booleanos](#4-operaciones-con-booleanos)
  * [4.1 Conceptos básicos](#41-conceptos-básicos)
  * [4.2 Problemas](#42-problemas)

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

## 3 Intercambio de valores

[ [Índice](#tabla-de-contenidos) ]

Muchos problemas requieren el intercambio de valores entre dos o más variables, por lo que en los siguientes ejercicios buscamos familiarizarnos con las técnicas que nos permiten realizar dicha tarea sin perder datos.

### 3.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **Intercambio:** supongamos que tenemos las variables *a = 2* y *b = -9*. Un intercambio entre ambas variables significaría que *a* pasa a valer lo que tenía *b* y viceversa, quedando *a = -9* y *b = 2*.

    Mentalmente este cambio luce trivial, pero cuando se analiza el procedimiento paso por paso, se puede notar que es posible perder el valor de una de las variables en el camino:

    0. **a <- 2; b <- (-9)** (valores iniciales)

    1. **a <- b** (primer paso del intercambio)

    2. **b <- a** (último paso del intercambio)

    Asumiento que esos son los pasos correctos, las variables tendrían los siguientes valores durante el procedimiento.

    | PASO | a | b |
    |---|---|---|
    | 0 | 2 | -9 |
    | 1 | -9 | -9 |
    | 2 | -9 | -9 |

    Se puede observar que en el paso número 2, a la variable *b* se le asigna (<-) el valor de *a*, pero *a* ya no tiene su valor inicial por lo que *b* obtiene un valor incorrecto. Incluso si se invierte el orden del procedimiento, se manifestaría el mismo problema:

    0. a <- 2; b <- (-9)

    1. b <- a

    2. a <- b

    | PASO | a | b |
    |---|---|---|
    | 0 | 2 | -9 |
    | 1 | 2 | 2 |
    | 2 | 2 | 2 |

    El problema es que se pierde el valor inicial de la variable que se modifica en el primer paso del procedimiento. Para lograr correctamente el intercambio, se hace necesario respaldar el valor de tal variable antes de modificarla, como se muestra a continuación:

    0. a <- 2; b <- (-9)

    1. t <- b

    2. b <- a

    3. a <- t

    | PASO | a | b | t |
    |---|---|---|---|
    | 0 | 2 | -9 | ? |
    | 1 | 2 | -9 | -9 |
    | 2 | 2 | 2 | -9 |
    | 3 | -9 | 2 | -9 |

    La variable *t* almacena el valor de la primera variable a modificar, cuestión de luego poder asignárselo a la segunda variable del intercambio. A este tipo de variables les llamamos *auxiliares*.

### 3.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

A partir de este punto, cuando no se especifique el tipo de entrada, el lector podrá escoger la que quiera en la solución. Sin embargo, se recomienda seguir practicando ambos tipos de entrada, con el propósito de lograr familiaridad con el lenguaje que está estudiando. Los ejercicios son los siguientes:

1. Escriba un programa que reciba dos números enteros *a* y *b*, para luego intercambiarlos internamente en el código, es decir, *a* pasa a tener el valor de *b* y *b* pasa a tener el valor que tenía *a* inicialmente. Finalmente, mostrar los valores finales de ambas variables.

2. Realice una aplicación que lea tres caracteres por separado, *c1*, *c2* y *c3*, para luego intercambiar *c1* con *c3*, seguido de *c2* y *c1*. Finalmente, mostrar los valores de *c1*, *c2* y *c3* mediante la salida estándar.

    Ejemplo:

    * **Entrada:**

        * **c1:** M

        * **c2:** x

        * **c3:** b

    * **Salida:**

        * **c1:** x

        * **c2:** b

        * **c3:** M

3. Realice un programa que lea dos oraciones *s1* y *s2*, así como un número entero *n*. El programa deberá intercambiar, el caracter *n* entre las oraciones, para luego mostrarlas. Nótese que para este problema, el primer caracter de la oración es *n = 1* y no *n = 0*.

    Por ejemplo:

    * **Entrada:**

        * **s1:** Mario lava la batea

        * **s2:** El mondongo es dulce y grasoso

        * **n:** 4

    * **Salida:**

        * **s1:** Marmo lava la batea

        * **s2:** El iondongo es dulce y grasoso

    Otro ejemplo:

    * **Entrada:**

        * **s1:** Erasmo me cortó el pelo

        * **s2:** Árbol de fruta

        * **n:** 1

    * **Salida:**

        * **s1:** Árasmo me cortó el pelo

        * **s2:** Erbol de fruta

    * **Nota:** el usuario en ningún caso podrá ingresar un *n < 1*, ya que no hay ningún caracter antes del 1.

    * **Consejo:** como los índices en algunos lenguajes empiezan por cero (0), se le puede restar uno (1) a *n* para encontrar el índice correcto.

4. Realice un programa que reciba una oración *s* y dos números enteros, *n* y *m*. El programa deberá intercambiar los caracteres *n* y *m* de la oración.

    Ejemplo:

    * **Entrada:**

        * **s:** la p**u**erta HA cerrado

        * **n:** 5

        * **m:** 13

    * **Salida:** la p erta HA**u**cerrado

    * **Nota:** el primer caracter de la oración corresponde a *n = 1*.

5. Realice un programa que lea dos oraciones *s1* y *s2*, así como dos números enteros *n1* y *n2*, para luego hacer los siguientes cambios:

    1. Intercambio entre *n1* de *s1* y *n2* de *s2*

    2. Intercambio entre *n2* de *s1* y *n1* de *s2*

    Escribir, en la salida, las dos oraciones que resultaron después de los intercambios.

    Por ejemplo:

    * **Entrada:**

        * **s1:** **E**ras**m**o me cortó el pelo

        * **s2:** **Á**rbo**l** de fruta

        * **n1:** 1

        * **n2:** 5

    * **Salida:**

        * **s1:** **l**ras**Á**o me cortó el pelo

        * **s2:** **m**rbo**E** de fruta

## 4 Operaciones con booleanos

[ [Índice](#tabla-de-contenidos) ]

Las operaciones con booleanos son aquellas en las que intervienen valores de tipo booleano, ya sea como operandos o como resultado de las operaciones. Estas son fundamentales para la ramificación del flujo de ejecución del problema; en otras palabras, el programa hará una cosa u otra, dependiendo de las condiciones planteadas en el código.

### 4.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **Booleanos:** los valores booleanos son aquellos que están en el rango [*true*, *false*], es decir, que solo pueden ser *verdadero* a *falso*. Dichos valores pueden aparecer como resultado de otras operaciones. Por ejemplo:

  * 1 < 2 -> **true**

  * 1 > 2 -> **false**

  * 2 >= 1 -> **true**

  * 2 = 1 -> **false** (en algunos lenguajes como C++, se utiliza el == en vez de = como operador de igualdad)

* **Operadores booleanos:** estos son aquellos que operan sobre valores de tipo booleano, entre ellos *and*, *or* y *not*. Los siguientes serían ejemplo de su uso:

    true **and** false -> **false**

    **not** false -> **true**

    (5 <= 1) **or** **not** false -> **true**

### 4.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

1. Escriba un programa que reciba dos números enteros, *a* y *b* y muestre el resultado de las siguientes operaciones lógicas.

    * a and b

    * a or b

    * not b

    * not b and a

    * a > b or b

    * b not equal a (a != b)

    Ejemplo:

    * **Entrada:**

        * **a:** 7

        * **b:** 0

    * **Salida:**

        * 7 and 0 -> 0 (false)

        * 7 or 0 -> 1 (true)

        * not 0 -> 1 (true)

        * not 0 and 7 -> 1 (true)

        * 7 > 0 or 0 -> 1 (true)

        * 0 not equal 7 -> 1 (true)

2. En este ejercicio escribiremos un validador interactivo. La idea general es que el usuario responda una serie de preguntas, y el programa le indique si sus respuestas son correctas. Para ello, primeramente, el usuario debe introducir tres números enteros *a*, *b* y *c*. Luego el programa debe realizar las siguientes preguntas:

    1. **a** and **b** or **c**

    2. **b** > **c** equals not **a**

    3. **a** equals **c** || **a** >= **b** && not **c**

    4. **c** xor **b**

    Luego de cada pregunta, el programa debe esperar que el usuario introduzca la respuesta, para luego decirle si fue correcta (1) o incorrecta (0). En resumen, el algoritmo del programa es el siguiente:

    1. Recibir valores de *a*, *b* y *c*. Se recomienda usar argumentos de programa para facilitar las pruebas.

    2. Mostrar primera pregunta.

    3. Leer respuesta de primera pregunta.

    4. Indicarle al usuario la correctitud de su respuesta. **1** es correcto y **0** es incorrecto.

    5. Mostrar segunda pregunta.

    6. Leer respuesta de segunda pregunta.

    7. Indicarle al usuario la correctitud de su respuesta. **1** es correcto y **0** es incorrecto.

    8. Repetir el procedimiento con las últimas dos preguntas.

    Ejemplo:

    * **Entrada (valores iniciales):**

        * **a:** 9

        * **b:** -5

        * **c:** 0

    * **Flujo del programa:**

        1. **Salida:** "Introduzca el resultado de: **9 and -5 or 0**"

        2. **Entrada:** 1

        3. **Salida:** "Fue correcta su respuesta? **1**"

        4. **Salida:** "Introduzca el resultado de: **-5 > 0 equals not 9**"

        5. **Entrada:** 0

        6. **Salida:** "Fue correcta su respuesta? **0**"

        7. **Salida:** "Introduzca el resultado de: **9 equals 0 || 9 >= -5 && not 0**"

        8. **Entrada:** 1

        9. **Salida:** "Fue correcta su respuesta? **1**"

        10. **Salida:** "Introduzca el resultado de: **0 xor -5**"

        11. **Entrada:** 0

        12. **Salida:** "Fue correcta su respuesta? **0**"

    * **Explicación:** primero se le pregunta al usuario mediante la salida estándar. Luego se lee la respuesta del usuario mediante la entrada estándar y, finalmente, se le indica al usuario la validez de su respuesta mediante la salida estándar. Este proceso de tres pasos se repite unas cuatro veces.

    * **Consejo:** así como se pueden comparar operandos, es posible comparar la respuesta correcta del ejercicio con la respuesta del usuario. Por ejemplo:

        ```cpp
        int resp_correcta = 5 + 1 * 4;
        int resp_usuario;

        cin >> resp_usuario;

        bool resultado = resp_correcta == resp_usuario;
        ```

    En este ejemplo se puede observar que se debe usar el operador de igualdad (== en C++) para comparar una respuesta con otra. Quedaría por parte del usuario encontrar la **resp_correcta** para cada pregunta, compararla con lo que introdujo el usuario (**resp_usuario**) y mostrar el **resultado** en la salida estándar.
