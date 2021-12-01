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

* [5 Condiciones](#5-condiciones)

  * [5.1 Conceptos básicos](#51-conceptos-básicos)

  * [5.2 Problemas](#52-problemas)

* [6 Ciclos](#6-ciclos)

  * [6.1 Conceptos básicos](#61-conceptos-básicos)

  * [6.2 Problemas](#62-problemas)

* [7 Estructuras de datos](#7-estructuras-de-datos)

  * [7.1 Conceptos básicos](#71-conceptos-básicos)
  
  * [7.2 Problemas](#72-problemas)

* [8 Ciclos anidados y matrices](#8-ciclos-anidados-y-matrices)

  * [8.1 Conceptos básicos](#81-conceptos-básicos)
  
  * [8.2 Problemas](#82-problemas)

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

6. Dominguito tiene un corral con 4 gallinas que cada vez tienen más crías, por lo que se le hace imposible mantener su patio limpio. Para lidiar con esta situación y conociendo el peso de cada gallina, decidió que se comerá a la más gorda en una sopa, mientras que apartará la más flaca a un corral aparte, para que ponga huevos tranquilamente.

    El problema es que él, incluso teniendo los pesos, no sabe cómo determinar cuál es el menor y cuál es el mayor. Por favor, haga un programa que ayude a Dominguito a encontrar la respuesta.

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

3. En este ejercicio escribiremos un validador interactivo. La idea general es que el usuario responda una serie de preguntas, y el programa le indique si sus respuestas son correctas.

    Para ello, primeramente, el usuario debe introducir un número entero *a* y luego dos números enteros *b* y *c* **en cualquier orden**. De estos dos último datos, *b* corresponde al menor de los números y *c* al mayor.

    Por ejemplo:

    * **Entrada (valores iniciales que introduce el usuario):**

        * 9 (primer número)

        * 0 (segundo número)

        * -5 (tercer número)

    * **Variables resultantes:**

        * **a:** 9 (siempre es el primer número)

        * **b:** -5 (siempre es el menor de los dos últimos números)

        * **c:** 0 (siempre es el mayor de los dos últimos números)

    Otro ejemplo:

    * **Entrada (valores iniciales que introduce el usuario):**

        * 1500 (primer número)

        * 5 (segundo número)

        * 9 (tercer número)

    * **Variables resultantes:**

        * **a:** 1500 (siempre es el primer número)

        * **b:** 5 (siempre es el menor de los dos últimos números)

        * **c:** 9 (siempre es el mayor de los dos últimos números)

    Luego de leer los números desde la entrada y asignarlos a las variables correspondientes, el programa debe realizar las siguientes preguntas:

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

## 5 Condiciones

[ [Índice](#tabla-de-contenidos) ]

Las sentencias y expresiones condicionales permiten expresar multiples caminos de ejecución en un mismo programa. Esto significa que el camino de ejecución a seleccionar por el programa dependerá de las condiciones que se presenten en el mismo.

### 5.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **if-else**: las sentencias condicionales se suelen expresar mediante las palabras *if* y *else*, cada uno seguido de un bloque de código que se desea ejecutar.

    En C++ la sintaxis es la siguiente:

    ```cpp
    if (/* AQUÍ CONDICIÓN (BOOLEANO) */)
    {
        // AQUÍ LO QUE DEBE SUCEDER SI LA CONDICIÓN ES CIERTA
    }
    else
    {
        // AQUÍ LO QUE DEBE SUCEDER SI LA CONDICIÓN ES FALSA
    }
    ```

    En el siguiente ejemplo, el programa mostraría *CAMINO 1*:

    ```cpp
    if (true)
    {
        cout << "CAMINO 1" << endl;
    }
    else
    {
        cout << "NUNCA PASARÉ POR AQUÍ" << endl;
    }
    ```

    ... mientras que en el siguiente ejemplo, el programa mostraría *CAMINO 2*:

    ```cpp
    if (false)
    {
        cout << "NUNCA PASARÉ POR AQUÍ" << endl;
    }
    else
    {
        cout << "CAMINO 2" << endl;
    }
    ```

    En este otro ejemplo, la condición que se evalúa es *a != b && c || b*. Como el resultado es *false*, se ejecuta el código del bloque del *else*.

    ```cpp
    bool a = true;
    bool b = false;
    bool c = false;

    if (a != b && c || b)
    {
        cout << "NUNCA PASARÉ POR AQUÍ" << endl;
    }
    else
    {
        cout << "YO SOY EL MENSAJE QUE SE MOSTRARÁ" << endl;
    }
    ```

### 5.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

1. Dominguito no quedó conforme con el programa que recibió la última vez, ya que varias de sus gallinas **pueden** pesar lo mismo, así que no sabría cual escoger si solo le dicen los pesos como respuesta. Necesita que le digan cuál de las cuatro gallinas matar y cuál encerrar en el corral apartado. Para ello, podríamos considerar el siguiente ejemplo:

    * **Entrada:**

        * **Gallina nro. 1:** 10

        * **Gallina nro. 2:** 15

        * **Gallina nro. 3:** 9

        * **Gallina nro. 4:** 15

    * **Salida:** debe cocinar a la gallina nro. 4 y encerrar la nro. 3.

    * **Salida (alternativa):** debe cocinar a la gallina nro. 2 y encerrar la nro. 3.

    * **Razonamiento:** ambas salidas son válidas ya que la gallina nro. 2 y la nro. 4 tienen el mismo peso, y ambas son las más gordas. La mejora está en que Dominguito ahora sabrá exactamente cual matar y no se confundirá cuando vea que dos de ellas pesan lo mismo.

2. En el mundo de las matemáticas, la división por cero resulta en un número **indefinido**. Eso significa que, por ejemplo, es imposible saber el resultado de la división 5/0. Lo mismo pasa en los programas computacionales; por lo general, dividir un número entre cero genera un *error en tiempo de ejecución*. En tales casos, la tarea del programador es **anticipar** dichos errores, evitando que la aplicación termine de manera inesperada.

    En ese sentido, se necesita un programa que reciba dos números enteros *n* y *m* por parte del usuario, para realizar la división de *n/m* y mostrar el resultado. Sin embargo, en caso de que el usuario introduzca un *m = 0*, el programa deberá indicar, mediante un mensaje de error, que no es posible dividir entre cero.

3. Escriba un programa que reciba el nombre del usuario, su fecha de nacimiento y su color favorito. Seguidamente, la aplicación deberá preguntar por un número entero *n* que corresponderá a una opción. Las opciones deben hacer lo siguiente:

    * **0:** simplemente terminar el programa con una despedida.

    * **1:** mostrar la fecha de nacimiento del usuario.

    * **2:** mostrar el color favorito del usuario.

    * **3:** mostrar el nombre del usuario.

    * **Cualquier otro número:** indicarle al usuario que no existe esa opción.

4. En su trabajo diario, a Manchito le toca cargar bultos, pasar coleto y atender a los clientes en la caja registradora. Sin embargo, ya se cansó de tener que memorizar lo que tiene que hacer, por lo que prefiere que una aplicación le haga unas preguntas sencillas y le diga qué hacer. Las condiciones son las siguientes:

    * Si el piso está sucio, debe preguntar si alguien más tiene el coleto. En caso de que alguien más lo tenga, debe quedarse parado esperando, y si no, debe tomar el coleto e ir a limpiar.

    * Si el piso no está sucio, debe revisar cuántas personas hay en las cajas registradoras. Si hay más de tres, entonces debe quedarse parado esperando a que aparezca algo que hacer. De lo contrario, debe ir a ayudar a las cajas registradoras.

    Ejemplo 1:

    * **Salida:** ¿El piso está sucio?

    * **Entrada:** Sí

    * **Salida:** ¿Alguien más tiene el coleto?

    * **Entrada:** Sí

    * **Salida:** Manchito, quédate ahí esperando a que suelten el coleto.

    Ejemplo 2:

    * **Salida:** ¿El piso está sucio?

    * **Entrada:** No

    * **Salida:** ¿Cuántas personas hay en las cajas registradoras?

    * **Entrada:** 2

    * **Salida:** Manchito, anda a ayudar en las cajas registradoras.

5. César necesita un programa que cambie, por un asterisco, el caracter en la posición *n* de una oración. Él no sabe mucho sobre posiciones, así que puede introducir una que sea inválida. En tal caso, el programa deberá indicarle a César que se equivocó.

6. Christopher decidió intercambiar dos caracteres en una oración, en las posiciones *n* y *m*, siendo 0 < *n* < *m* <= *l*, en donde *l* es la longitud de la oración. No obstante, él no sabe cómo determinar si un número es menor que otro, así que es capaz de introducir valores inválidos. Ayuda a Christopher a introducir valores válidos para *n* y *m*, además de intercambiar los caracteres.

7. Los números de teléfono son difíciles de recordar. Es por ello que en épocas pasadas se acudía al uso de mnemónicos, es decir, palabras que sustituyen a dichos códigos de operación. En las siguiente tabla, se pueden observar los caracteres disponibles para construir las palabras:

    | Nro. | Caracteres |
    |---|---|
    | 1 | 1 |
    | 2 | ABC |
    | 3 | DEF |
    | 4 | GHI |
    | 5 | JKL |
    | 6 | MNO |
    | 7 | PQRS |
    | 8 | TUV |
    | 9 | WXYZ |
    | 0 | 0 |

    Esto significa que podemos escribir el número 2272 usando las combinaciones CASA, BARA ó CARA, entre otras posibilidades.

    Dicho eso, necesitamos una aplicación que verifique si el **número de tres dígitos** que *introdujo* el usuario corresponde al nemónico, **de igual longitud**, que *también introdujo* el usuario. De no corresponder, o de haber algún dato incompleto, el programa deberá mostrarle al usuario en qué se equivocó.

    **Nota:** los números pueden tener ceros a la izquierda. Por ejemplo, 001 es un número valido y su mnemónico correspondiente es 001.

8. Miguelito es de la generación Y, por lo que no sabe nada sobre mnemónicos. Sin embargo, en la universidad le pidieron que *decodifique* un grupo de tres letras. Escriba un programa que cubra dicha necesidad y que muestre mensajes de error descriptivos cuando Miguelito introduzca una palabra inválida.

    Por ejemplo:

    * **Entrada:** F0s

    * **Salida:** 307

    **Razonamiento:** La *F* corresponde al número *3*, el *cero* corresponde al *mismo número* y la *S* corresponde al número *7*.

9. Sergio estudia en la UDO, por lo que es obligatorio que vea, al menos, Matemática I. En esta materia, le mandaron un ejercicio que no logra resolver, así que decidió contratarnos para que le demos una solución basada en software. El ejercicio le da tres puntos en el plano, cada uno con coordenadas **X** y **Y**, y él debe responde cuál de los **últimos puntos** está más cerca **del primero** y cuál está más lejos.

10. Sergio entregó el ejercicio, pero el profesor sospechó que se copió, así que le mandó solo a él varios ejercicios en donde debe hacer lo mismo, pero con **más de tres puntos en el plano**. Razone brevemente, sin escribir ningún programa, ¿cómo se podría modificar el programa original para que funcione con más de tres puntos?

11. Pablo se metió en problemas con un cliente: entregó una aplicación que calcula los días que lleva el año actual, pero no consideró la posibilidad de que el año sea bisiesto. Realiza un programa que ayude a Pablo a saber si un año es bisiesto.

12. A Pablo le gustó el trabajo que hiciste, así que decidió pagarte USD 10.000 para que le hagas el programa que originalmente debía entregar él. Este consiste en decir cuántos días van de la fecha que el usuario introduce, la cual no necesariamente corresponde a la fecha actual, es decir, también puede ser una del pasado o futuro. Como programador, podrás decidir el formato en que el usuario ingresa la fecha.

13. Rafael fue a comprar una chupeta al negocio de Wasamara. Luego de pedir la paleta, solicitó al anciano descontarlo de su línea de crédito personal, a lo que Wasamara respondió con que él nunca fiaba y que a él, en particular, nunca lo había visto en su vida, así que debía pagar con dinero en efectivo como todos los demás. Rafael, enojado, pagó con 400 dólares americanos en efectivo.

    Si el dulce tenía un **precio de 164 dólares** y el vendedor tenía **disponible billetes de 500, 100, 50, 20, 10, 5, 2 y 1** para dar vuelto, ¿cuántos billetes de cada demoninación debía dar para completar el vuelto de Rafael? Realice un programa que permita resolver este problema para cualquier combinación de precio y monto pagado.

    Por ejemplo: ¿qué billetes tendría que dar de vuelto Wasamara si el cliente pagó 300 dólares para una compra de 211?

    **Nota:** el monto máximo posible para una compra es de 1.000 dólares americanos y nada es gratis en la tienda.

14. A Víctor le gustaría transformar, a números romanos, cantidades enteras positivas no mayores a *2021*. Escribe un programa que le provea de una solución.

    Ejemplo:

    * **Entrada:** 2021

    * **Salida:** MMXXI

    Otro ejemplo:

    * **Entrada:** 590

    * **Salida:** DXC

## 6 Ciclos

[ [Índice](#tabla-de-contenidos) ]

Algunos problemas requieren soluciones en las que es necesario repetir un procedimiento hasta que se cumpla cierta condición. Como ejemplos sencillo, encontramos las tareas de mostrar los números pertenecientes a una serie, mostrar un menú de manera reiterada hasta que el usuario decida abandonarlo y leer los elementos de una matriz.

Para un número determinado de operaciones, es posible cubrir todos estos casos con estructuras de ```if-else```, pero el código suele extenderse demasiado, sin mencionar que queda muy frágil ante cambios sencillos. En dicho sentido, existen estructuras llamadas *ciclos* (en inglés *loops*) que permiten representar un procedimiento que debe realizarse de manera repetitiva.

### 6.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

Cada lenguaje de programación suele proveer de ciertas herramientas para expresar ciclos; las siguientes están entre las más comunes:

* **```while```:** en este tipo de ciclo, se ejecutan una serie de instrucciones siempre que se de cierta condición. Por ejemplo, si *n* es mayor a 0, restarle 1 a *n*. Nótese que la acción de restar solo se ejecuta si la condición se da.

* **```do-while```:** a diferencia del ciclo *mientras*, el *hacer-mientras* no pregunta primero por la condición, si no que ejecuta primero las instrucciones que contiene y utiliza la condición para saber si debe continuar las siguientes iteraciones.

    **Nota:** una iteración es una vuelta del ciclo. Por ejemplo, cinco iteraciones significa que el código del ciclo se ejecutó cinco veces, y la tercera iteración se refiere a la tercera ejecución de dicho código.

* **```for```:** los *for* son una versión más sofisticada del ciclo *while*. En estos también se tiene una condición que determina si la siguiente iteración se debe ejecutar, teniendo a su vez otros dos parámetros en los que se puede controlar la manera en la que arranca y avanza el ciclo. Es especialmente útil para llevar el control del número de iteraciones.

* **Funciones recursivas**: otra forma de ejecutar un código de manera reiterada es ponerlo en una función y hacer que se llame a sí misma. Los lenguajes de programación funcional suelen utilizar este método, mientras que aquellos que se inclinan más por la programación imperativa suelen darle prioridad a los ```while```, ```do-while``` y ```for```.

### 6.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

1. Realice un programa que permita al usuario introducir un mensaje y, seguidamente, lo muestre de manera reiterada. La única forma de detener tal programa será cerrándolo de manera forzada, ya sea con *Ctrl + C* o cualquier otro método que provea el sistema operativo.

    Por ejemplo:

    * **Entrada:** Repite este mensaje

    * **Salida:**
        * Repite este mensaje

        * Repite este mensaje

        * Repite este mensaje

        * Repite este mensaje

        * Repite este mensaje

        * ...

2. Realice una aplicación que pregunte al usuario si desea ver el menú de opciones. Si el usuario responde que no, simplemente terminar la ejecución y, si responde que sí, mostrarle un menú con las siguientes opciones:

    0. Salir

    1. Seguir mostrando menú

    De seleccionar la opción 1, se le debe volver a mostrar el mismo menú al usuario. En cambio, si seleccionó la opción 0, el programa debe finalizar su ejecución.

    **Consejo:** analizar primero cuál de los ciclos disponibles es el mejor para ejecutar una tarea solo si *primero* se da cierta condición.

3. Realice una aplicación que muestre un menú con las siguientes opciones:

    0. Salir

    1. Seguir mostrando menú

    De seleccionar la opción 1, se le debe volver a mostrar el mismo menú al usuario. En cambio, si seleccionó la opción 0, el programa debe finalizar su ejecución.

    **Consejo:** analizar primero cuál de los ciclos disponibles es el mejor para ejecutar una tarea *al menos una vez* y luego preguntar por alguna condición para ver si se debe repetir el proceso.

4. Realice una aplicación que le solicite al usuario su nombre y luego muestre un menú con las siguientes opciones:

    0. Salir

    1. Mostrar su nombre

    De seleccionar la opción 1, el programa deberá mostrar al usuario su nombre y esperar a que el usuario introduzca cualquier cosa para volver a mostrar el menú. En cambio, si seleccionó la opción 0, el programa debe finalizar su ejecución.

    **Consejo:** al usar las funciones de lectura de la entrada, el programa quedará esperando hasta que se introduzca cualquier cosa. Sin embargo, se debe cuidar que las siguientes iteraciones del menú no queden datos en el buffer de entrada, ya que estos pueden interferir al momento de seleccionar la próxima opción.

5. Realice un programa que reciba un número entero mayor a cero y escriba, en la salida estándar, la cuenta regresiva desde tal número hasta cero.

    Por ejemplo:

    * **Entrada:** 5

    * **Salida:** 5 4 3 2 1 0

    Otro ejemplo:

    * **Entrada:** 1

    * **Salida:** 1 0

6. Realice un programa que reciba un número entero mayor a 1 y escriba, en la salida estándar, la cuenta progresiva desde 1 hasta dicho número.

    Por ejemplo:

    * **Entrada:** 5

    * **Salida:** 1 2 3 4 5

    Otro ejemplo:

    * **Entrada:** 2

    * **Salida:** 1 2

7. Realice un programa que reciba un número entero mayor a 1 y escriba, en la salida estándar, de tres en tres, la cuenta progresiva hasta ese número.

    Por ejemplo:

    * **Entrada:** 14

    * **Salida:** 1 4 7 10 13

    * **Razonamiento:** la cuenta va de tres en tres desde el 1, y termina cuando el siguiente a mostrar sea mayor al número introducido al usuario.

    Otro ejemplo:

    * **Entrada:** 3

    * **Salida:** 1

8. Realice un programa que reciba un número entero mayor o igual a tres y escriba, en la salida estándar, de tres en tres, la cuenta regresiva hasta cero.

    Por ejemplo:

    * **Entrada:** 11

    * **Salida:** 11 8 5 2

    * **Razonamiento:** La cuenta empieza en el número introducido por el usuario y en cada iteración se resta tres. La serie termina cuando el número a mostrar es menor a cero.

    Otro ejemplo:

    * **Entrada:** 3

    * **Salida:** 3 0

9. Realice un programa que reciba un número entero *n* y muestra la cuenta regresiva de los números impares, desde *n* hasta cero, en pasos de tres.

    Por ejemplo:

    * **Entrada:** 26

    * **Salida:** 23 17 11 5

    Otro ejemplo:

    * **Entrada:** 25

    * **Salida:** 25 19 13 7 1

10. Realice un programa que reciba un número entero *n* mayor o igual a 5 y haga la cuenta progresiva en pasos de dos desde 5 hasta dicho número y luego de vuelta hasta -9.

    Por ejemplo:

    * **Entrada:** 12

    * **Salida:** 5 7 9 11 9 7 5 3 1 -1 -3 -5 -7 -9

    Otro ejemplo:

    * **Entrada:** 9

    * **Salida:** 5 7 9 7 5 3 1 -1 -3 -5 -7 -9

    **Consejo:** considerar utilizar dos ciclos ```for```, uno seguido del otro y que el segundo continúe, de alguna manera, lo que estaba haciendo el primero.

## 7 Estructuras de datos

[ [Índice](#tabla-de-contenidos) ]

Un elemento clave en la resolución de problemas es la selección de estructuras de datos adecuadas. En la presente sección, se exploran algunos problemas básicos que se resuelven mejor empleando dichas estructuras.

### 7.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **Estructura de datos:** una estructura de datos es una forma particular de organizar datos en una computadora para que puedan ser utilizados de manera eficiente. Ejemplos de estructuras de datos incluyen vectores (también llamados arreglos) y pilas.

* **Vector:** un vector, también conocido como arreglo, es una serie de elementos en un orden específico. Se accede a los elementos utilizando un entero como índice para especificar el elemento que se requiere.

* **Pila:** una pila (stack en inglés) es una lista ordenada o estructura de datos que permite almacenar y recuperar datos, siendo el modo de acceso a sus elementos de tipo LIFO (del inglés Last In, First Out, último en entrar, primero en salir).

### 7.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

1. Realice un programa que muestre al usuario **un menú** con las siguientes opciones:

    * **a**. Solicita al usuario introducir un número y luego le dice si es par o impar.

    * **b**. Solicita al usuario introducir una oración y luego muestra cada uno de sus caracteres en líneas separadas. Por ejemplo:

        **Entrada:** Sí, no

        **Salida:**

        * S

        * í

        * , (esta es una coma)

        * &nbsp; (este es un espacio)

        * n

        * o

    * **x**. Salir

    **Nota:** es obligatorio usar las letras **a**, **b** y **x** como opciones. Si el usuario introduce una opción fuera de esas letras, se le debe solicitar que introduzca una opción válida. La única forma de salir del programa es ingresando *x* como opción.

2. Figueroa recibió sus notas de las últimas 5 materias del bachillerato. Las notas mayores o iguales a 10 corresponden a asignaturas aprobadas, mientras que el resto son las que reprobó. Él no entiende esto, así que decidió pagar 30.000 USD para que le construyan una aplicación que le diga, **por cada nota**, si aprobó o reprobó.

    **Nota:** en este problema es clave solicitarle a Figueroa que introduzca todas las notas **antes** de mostrarle cuáles corresponden a *aprobado* y cuáles a *reprobado*.

3. Zapata estudia en el mismo colegio que Figueroa y también desea que le construyan un programa que le diga las notas aprobadas y las reprobadas. El problema es que no se sabe de antemano cuántas materias vio Zapata, por lo que se debe diseñar su aplicación para un número **variable** de materias.

    **Nota:** cuando es cierto que no se sabe la cantidad de materias de antemano, se puede optar por que el programa le pregunte al usuario cuántas notas ingresará, para luego trabajar con dicho número como una variable en el código.

    **Límite:** Zapata no debe introducir más de 32 notas.

4. Édgar decidió relajarse este fin de semana con la manada de la urbanización. Compró licor e invitó a todos a su casa, para que participen en un juego de tragos. En cada ronda se siguen los pasos a continuación:

    * Se elige una letra.

    * En el sentido de las agujas del reloj, cada participante deberá decir una palabra por esa letra.

    * Si pasan 12 personas y ninguno se equivoca, todos deberán tomar un trago seco.

    * Por otro lado, el que se equivoque o tarde más de cinco segundos en responder, tendrá la oportunidad de decir, en orden inverso, **todas** las palabras que se han dicho en la ronda.

        * Si no logra decir todas las palabras en el orden correcto, le toca un trago seco.

        * Si logra decirlas correctamente, todos los demás deberán pagar la penitencia del trago seco.

    El problema es que es muy difícil recordar las palabras que han dicho los participantes, por lo que sería útil una aplicación que permita registrarlas, una por una, y luego mostrarlas en orden inverso a petición del usuario.

    **Nota:** en este caso de uso particular, a pesar de que se sabe que no pueden pasar más de 12 personas, es imposible saber al principio del juego cuántas personas pasarán antes de que alguien se equivoque, por lo que es recomendable preguntarle al usuario si desea mostrar las palabras registradas de manera reiterada.

5. Bárbara está organizando otra fiesta en la casa de Édgar. Dado el éxito que tuvo el juego de tragos en la oportunidad pasada, decidieron repetirlo pero modificando un poco las reglas, ya que la última vez todos utilizaron la aplicación que creaste, lo que los llevó a un estado de gran ebriedad. La idea por la que Bárbara está dispuesta a pagar 70.000 USD es la siguiente:

    * Se elige una letra.

    * En el sentido de las agujas del reloj, cada participante deberá decir una palabra por esa letra.

    * **A diferencia de la primera versión del juego**, no hay límite en cuanto a la cantidad de personas que pueden decir palabras correctas. La ronda simplemente continúa hasta que alguien se equivoque.

    * Por otro lado, el que se equivoque o tarde más de cinco segundos en responder, tendrá la oportunidad de decir, en orden inverso, **todas** las palabras que se han dicho en la ronda.

        * Si no logra decir todas las palabras en el orden correcto, le toca un trago seco.

        * Si logra decirlas correctamente, todos los demás deberán pagar la penitencia del trago seco.

    El problema es que es muy difícil recordar las palabras que han dicho los participantes, por lo que sería útil una aplicación que permita registrarlas, una por una, y luego mostrarlas en orden inverso a petición del usuario.

6. Dado que la última fiesta de Bárbara fue un éxito, decidió repetirla pero esta vez en la casa de Tomás, el señor que vende pollos. También, desea contratarte nuevamente para que hagas una pequeña modificación a la aplicación que va almacenando las palabras que se dicen en el juego, debido a que llegaba a un punto en el que tocaba decir demasiadas palabras, tantas que era preferible perder a propósito y beber hasta quedar muy ebrio. Aquí las reglas ligeramente modificadas:

    * Se elige una letra.

    * En el sentido de las agujas del reloj, cada participante deberá decir una palabra por esa letra.

    * No hay límite en cuanto a la cantidad de personas que pueden decir palabras correctas. La ronda simplemente continúa hasta que alguien se equivoque.

    * Por otro lado, el que se equivoque o tarde más de cinco segundos en responder, tendrá la oportunidad de decir, **en orden**, las primeras palabras que se dijeron en el juego.

        * **Si son muchas palabras, basta con que diga las primeras 12. Si son menos, es necesario que las diga todas.**

        * Si no logra decir todas las palabras en el orden correcto, le toca un trago seco.

        * Si logra decirlas correctamente, todos los demás deberán pagar la penitencia del trago seco.

    El problema es que es muy difícil recordar las palabras que han dicho los participantes, por lo que sería útil una aplicación que permita registrarlas, una por una, y luego mostrarlas en orden inverso a petición del usuario.

    **Nota:** a diferencia de las otras fiestas, las palabras se deberán en el mismo orden que fueron dichas y no en orden inverso.

7. Las gallinas de Dominguito se multiplicaron, tanto asi que ahora posee 10 lotes cada uno con 5 gallinas gordas, y cada cierto tiempo debe sacar a cierta gallina a pelarse a la barberia.

    El problema es que Dominguito ultimamente tiene muy mala memoria, y detesta que cada vez que tenga que sacar a pelar a cierta gallina especifica, se tenga que mover y revisar cada uno de los lotes, aparte de eso 7 de esas gallinas requieren cuidados especiales para poder pelarse por lo que deben ir a una barberia especial.

    Dominguito entonces necesita una solucion a su problema, asi que para solucionarlo penso en pasar por la casa de cumana ii robar algunas cosas y luego venderlas en pantanillo, y de esa forma poder pagarle a un programador y que este le diseñe una aplicacion para lo siguiente:

    1. poder enumerar cinco gallinas o mas en cada lote para asi poder ver desde la pc o el telefono donde esta la gallina que necesita pelar, y asi el no tenga que moverse y hacer esfuerzo alguno

    2. seleccionar una de esas gallinas y que la aplicacion le recuerde, si esa gallina debe ir a pelarse a una barberia especial o no. Debido a que el ya esta harto de esforzarse mentalmente y recordar cual de las gallinas requieren un pelado especial.

    **Nota:** dominguito de antemano sabe estas cosas, pero el siente que las puede olvidar, por esa razon antes de olvidarlas las quire anotar en el programa. Para que despues el no tenga que esforzarse y el programa haga todo por el, y asi el cuide su fisico y su memoria

8. Abuelo formateo su computadora por que el otro dia la infecto de virus bajando algo por ares, y luego de haberla formateado intento instalar los siguientes programas:

    * Emule = 2 gb

    * Ares = 500 mb

    * Limewire = 10gb

    * Frostwire 10 mb

    * Aresplus = 20 gb

    * Google chrome = 2 gb

    * Nero 230 = mb

    * Nero premium 2 gb

    * Avast = 5 gb

    * Norton 13 gb

    Pero windows xp no se lo permitio por 2 razones. La primera es que la computadora solo tiene 52,7 gbs de espacio, pero el realmente no sabe cuanto pesa cada programa, y se le hace dificil averiguarlo, y calcularlo, y el otro problema es que uno de los programas no es compatible con windows xp, parece ser uno de los antivirus, por lo que decidio pedirle a panina que le programara una aplicacion, la cual se encargue de hacerle una lista con los programas disponibles, para luego preguntarle cual desea instalar y que le diga si es posible instalar los programas seleccionados o no.

    El programa debe hacer lo siguiente:

    1. mostrar una lista con los programas disponibles

    2. preguntarle al usuario cuales desea instalar

    3. decirle si es posible instalar los programas seleccionados o no. Ya sea por que no alcanza el espacio, o por que esta en la lista hay un programa que no es compatible con windows xp

    **Nota:**

    * el programador debe elegir cual de esos antivirus sera el que no es compatible con windows xp.

    * si alguno de los programas incluidos no es compatible con windows xp, el programa debe de mostrar cual de los programas es incompatible.

## 8 Ciclos anidados y matrices

[ [Índice](#tabla-de-contenidos) ]

Para recorrer una estructura *lineal*, como los vectores o los arreglos, suele ser necesario el uso de ciclos. No obstante, en ocasiones estas estructuras lineales contienen, en cada elemento, otras estructuras que también se pueden recorrar, como es el caso de la lista de listas, lista de mapas, mapa de listas, entre muchos otros casos. En este contexto, un caso bastante particular y común es la matriz, la cual representa un arreglo de arreglos y que es más fácil de recorrer empleando lo que llamamos *ciclos anidados*.

### 8.1 Conceptos básicos

[ [Índice](#tabla-de-contenidos) ]

* **Ciclo anidado:** un ciclo anidado es aquel que se encuentra dentro de otro ciclo. Por ejemplo, un ```do-while``` dentro de un ```for``` o un ```for``` dentro de otro ```for```. No hay límite en cuanto al nivel de anidamiento, lo que significa se pueden tener ciclos anidados dentro de otros ciclos que, a su vez, están anidados incluso dentro de otros ciclos. No obstante, se debe tener cuidado con el nivel de anidamiento, ya que, dependiendo de la tarea que se esté realizando, puede tener un impacto sobre el rendimiento del código y sobre la *complejidad ciclomática*.

* **Matriz:** una matriz es un arreglo de arreglos. Suelen representar tablas, en las que una de las dimensiones corresponde a las filas y la otra a las columnas. Es común que estas se recorran mediante un ciclo anidado dentro de otro, en donde el ciclo más externo recorre una dimensión y el más interno la otra dimensión. Por ejemplo, un par de ```for```, en donde el ```for``` externo recorre las filas de la matriz y el ```for``` interno las columnas **de cierta fila** de la matriz.

* **Figuras con ciclos anidados:** otra utilidad un tanto curiosa de los ciclos anidados es que permiten recorrer en formas particulares. Por ejemplo, hacer un recorrido en zig-zag, en forma de X o incluso en forma de alguna letra del alfabeto.

### 8.2 Problemas

[ [Índice](#tabla-de-contenidos) ]

1. Escriba un programa que reciba un número entero *d* y recorra de 0 hasta *d* en dos dimensiones. En cada paso de la dimensión exterior se deberán mostrar *d* asteriscos seguidos de un salto de línea. Por ejemplo, para una dimensión 5 introducida por el usuario el programa deberá mostrar lo siguiente:

    \*\*\*\*\*

    \*\*\*\*\*

    \*\*\*\*\*

    \*\*\*\*\*

    \*\*\*\*\*

    Esas son cinco filas, cada una con cinco asteríscos.

2. Escriba un programa que muestre una matriz de asteriscos de dimensiones *n* (filas) y *m* (columnas), ambas especificadas por el usuario mediante la entrada del programa.

    Por ejemplo:

    * **Entrada:**

        * **Filas:** 3

        * **Columnas:** 4

    * **Salida:**

        \*\*\*\*

        \*\*\*\*

        \*\*\*\*

    **Nota:** el usuario podrá introducir cero como valor de las dimensiones.

3. Escriba un programa que reciba dos dimensiones *n* y *m* y muestre una matriz en la que cada fila será la serie desde 1 hasta *m*.

    Por ejemplo:

    * **Entrada:**

        * **Filas:** 3

        * **Columnas:** 4

    * **Salida:**

        1 2 3 4

        1 2 3 4

        1 2 3 4

4. Escriba un programa que reciba dos dimensiones *n* y *m* y muestre una matriz en la que cada celda contenga el valor de su posición.

    Por ejemplo:

    * **Entrada:**

        * **Filas:** 3

        * **Columnas:** 4

    * **Salida:**

        ```text
        1  2  3  4
        5  6  7  8
        9 10 11 12
        ```

    * **Consejo:** analizar cómo apoyarse en el número de la fila para determinar el número de la columna. Esto significa entender por qué la primera fila empieza en 1, la segunda en 5 y la última en 9, cómo se relacionan estos números a la fila que se está recorriendo en ese momento.

5. Haga una aplicación que solicite al usuario dos dimensiones y muestre, en la salida estándar, una matriz en donde el valor de cada celda es su posición, pero en orden inverso. Es decir, la primera celda es el último número y la última celda es el primer número.

    Por ejemplo:

    * **Entrada:**

        * **Filas:** 3

        * **Columnas:** 4

    * **Salida:**

        ```text
        12 11 10 9
         8  7  6 5
         4  3  2 1
        ```

6. Realize un programa que reciba dos dimensiones y muestre la primera fila y la primera columna de una matriz con tales dimensiones, y en donde cada celda es el valor de su posición.

    Por ejemplo:

    * **Entrada:**

        * **Filas:** 3

        * **Columnas:** 4

    * **Salida:**

        ```text
        1 2 3 4
        5 
        9
        ```

    * **Consejo:** el camino para solucionar este tipo de problemas es hacer dos ```for``` anidados **sencillos** y poner dentro del ```for``` más interno algo que decida si se debe mostrar o no el número que se está recorriendo.

7. Realize un programa que reciba una dimensión y muestre la **diagonal principal** de una matriz cuadrada con dicha dimensión. Una matriz cuadrada es una matriz en la cual el número de filas es igual al número de columnas.

    Por ejemplo:

    * **Entrada:** 4

    * **Salida:**

        ```text
        1
           6
             11
                16
        ```

    * **Consejo:** el camino para solucionar este tipo de problemas es hacer dos ```for``` anidados **sencillos** y poner dentro del ```for``` más interno algo que decida si se debe mostrar o no el número que se está recorriendo.

8. Realize un programa que reciba una dimensión y muestre la **diagonal inversa** de una matriz cuadrada con dicha dimensión.

    Por ejemplo:

    * **Entrada:** 4

    * **Salida:**

        ```text
                  4
               7
           10
        13
        ```

9. Escriba un programa que reciba una dimensión D y muestre las iniciales de su nombre, cada una con una altura cercana a D.

    Por ejemplo:

    * **Entrada:** 5

    * **Salida:**

        ```text
        *           *
        *  *     *  *
        *     *     *
        *           *
        *           *
        ```

        ```text
             *
            * *
           *   *
          * * * *
         *       *
        *         *
        ```

        ```text
        *  *  *  *
        *
        *
        *
        *
        *  *  *  *
        ```

        ```text
        *
        *
        *
        *
        *  *  *
        ```

    * **Nota:** una altura cercana a la dimensión que introduce el usuario es aquella que es igual o mayor por, a lo sumo, un número de D. Por ejemplo, la altura 6 es cercana a la dimensión 5. En otro ejemplo, la altura 7 ya no es cercana a la dimensión 5.

    * **Consejo:** escribir cada letra en una función, con el propósito de que el esfuerzo de diseñar cada una no interfiera con el de las otras letras. Cada función puede recibir la dimensión y decidir, internamente, la forma en la que mostrará la letra.
