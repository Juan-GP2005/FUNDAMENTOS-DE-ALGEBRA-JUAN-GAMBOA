# Guía de Ejercicios de Conversión Numérica y Álgebra

## Realiza las conversiones de binario a decimal

**73)** `00001111`

* **Desarrollo:**

  ```
  Posiciones:  2^7  2^6  2^5  2^4  2^3  2^2  2^1  2^0
  Bits:         0    0    0    0    1    1    1    1
  ```

  * $2^0 \cdot 1 = 1$

  * $2^1 \cdot 1 = 2$

  * $2^2 \cdot 1 = 4$

  * $2^3 \cdot 1 = 8$

  * **Suma:** $8 + 4 + 2 + 1 = 15_{10}$

* **Resultado:** $(15)_{10}$

**74)** `10011001`

* **Desarrollo:**

  ```
  Posiciones:  2^7  2^6  2^5  2^4  2^3  2^2  2^1  2^0
  Bits:         1    0    0    1    1    0    0    1
  ```

  * $2^0 \cdot 1 = 1$

  * $2^3 \cdot 1 = 8$

  * $2^4 \cdot 1 = 16$

  * $2^7 \cdot 1 = 128$

  * **Suma:** $128 + 16 + 8 + 1 = 153_{10}$

* **Resultado:** $(153)_{10}$

**75)** `11001100`

* **Desarrollo:**

  ```
  Posiciones:  2^7  2^6  2^5  2^4  2^3  2^2  2^1  2^0
  Bits:         1    1    0    0    1    1    0    0
  ```

  * $2^2 \cdot 1 = 4$

  * $2^3 \cdot 1 = 8$

  * $2^6 \cdot 1 = 64$

  * $2^7 \cdot 1 = 128$

  * **Suma:** $128 + 64 + 8 + 4 = 204_{10}$

* **Resultado:** $(204)_{10}$

**76)** `01111011`

* **Desarrollo:**

  ```
  Posiciones:  2^7  2^6  2^5  2^4  2^3  2^2  2^1  2^0
  Bits:         0    1    1    1    1    0    1    1
  ```

  * $2^0 \cdot 1 = 1$

  * $2^1 \cdot 1 = 2$

  * $2^3 \cdot 1 = 8$

  * $2^4 \cdot 1 = 16$

  * $2^5 \cdot 1 = 32$

  * $2^6 \cdot 1 = 64$

  * **Suma:** $128 + 64 + 32 + 16 + 8 + 2 + 1 = 251_{10}$

* **Resultado:** $(251)_{10}$

**77)** `00000000 11111111`

* **Desarrollo:**

  ```
  Bits:  00000000  11111111
  ```

  * $2^0 \cdot 1 = 1$

  * $2^1 \cdot 1 = 2$

  * $2^2 \cdot 1 = 4$

  * $2^3 \cdot 1 = 8$

  * $2^4 \cdot 1 = 16$

  * $2^5 \cdot 1 = 32$

  * $2^6 \cdot 1 = 64$

  * $2^7 \cdot 1 = 128$

  * **Suma:** $128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 255_{10}$

* **Resultado:** $(255)_{10}$

**78)** `00000010 00000000`

* **Desarrollo:**

  ```
  Posición del bit '1': 2^9
  ```

  * $2^9 = 512$

* **Resultado:** $(512)_{10}$

## Convierte de binario a octal

> **Tabla de equivalencias (Binario a Octal):**
>
> * `000` = 0 | `001` = 1 | `010` = 2 | `011` = 3
>
> * `100` = 4 | `101` = 5 | `110` = 6 | `111` = 7

**79)** `11010101`

* **Desarrollo:** Agrupando en tríadas desde la derecha:

  ```
  011  010  101
   3    2    5
  ```

* **Resultado:** $325_8$

**80)** `01101110`

* **Desarrollo:** Agrupando en tríadas:

  ```
  001  101  110
   1    5    6
  ```

* **Resultado:** $156_8$

**81)** `10110011`

* **Desarrollo:** Agrupando en tríadas:

  ```
  010  110  011
   2    6    3
  ```

* **Resultado:** $263_8$

**82)** `00000000 11111111`

* **Desarrollo:** Agrupando en tríadas:

  ```
  000  000  000  011  111  111
   0    0    0    3    7    7
  ```

* **Resultado:** $000,377_8$ (o simplemente $377_8$)

**83)** `00000011 11000000`

* **Desarrollo:** Agrupando en tríadas:

  ```
  000  000  011  110  000  000
   0    0    3    6    0    0
  ```

* **Resultado:** $003,600_8$ (o $3600_8$)

**84)** `00000101 01010101`

* **Desarrollo:** Agrupando en tríadas:

  ```
  000  000  101  010  101  010  101  -->  000  000  101  010  101  101
   0    0    6    1    2    6
  ```

* **Resultado:** $006,126_8$

## Convierte de binario a hexadecimal

> **Tabla de equivalencias (Binario a Hexadecimal):**
>
> * `0000` = 0 | `0001` = 1 | `0010` = 2 | `0011` = 3
>
> * `0100` = 4 | `0101` = 5 | `0110` = 6 | `0111` = 7
>
> * `1000` = 8 | `1001` = 9 | `1010` = A (10) | `1011` = B (11)
>
> * `1100` = C (12) | `1101` = D (13) | `1110` = E (14) | `1111` = F (15)

**85)** `11011010`

* **Desarrollo:** Agrupando en cuartetos:

  ```
  1101  1010
    D     A
  ```

* **Resultado:** $\text{DA}_{16}$

**86)** `01111100`

* **Desarrollo:** Agrupando en cuartetos:

  ```
  0111  1100
    7     C
  ```

* **Resultado:** $7\text{C}_{16}$

**87)** `10110101`

* **Desarrollo:** Agrupando en cuartetos:

  ```
  1011  0101
    B     5
  ```

* **Resultado:** $\text{B5}_{16}$

**88)** `11110000 10100101`

* **Desarrollo:** Agrupando en cuartetos:

  ```
  1111  0000  1010  0101
    F     0     A     5
  ```

* **Resultado:** $\text{F0A5}_{16}$

**89)** `00001111 00001111`

* **Desarrollo:** Agrupando en cuartetos:

  ```
  0000  1111  0000  1111
    0     F     0     F
  ```

* **Resultado:** $0\text{F}0\text{F}_{16}$

**90)** `10000000 00000001`

* **Desarrollo:** Agrupando en cuartetos:

  ```
  1000  0000  0000  0001
    8     0     0     1
  ```

* **Resultado:** $8001_{16}$

## Convierte de octal a binario

**91)** `325`

* **Desarrollo:**

  ```
  3 -> 011
  2 -> 010
  5 -> 101
  ```

* **Resultado:** `11010101`$_2$

**92)** `156`

* **Desarrollo:**

  ```
  1 -> 001
  5 -> 101
  6 -> 110
  ```

* **Resultado:** `01101110`$_2$

**93)** `377`

* **Desarrollo:**

  ```
  3 -> 011
  7 -> 111
  7 -> 111
  ```

* **Resultado:** `11111111`$_2$

**94)** `01777`

* **Desarrollo:**

  ```
  0 -> 000
  1 -> 001
  7 -> 111
  7 -> 111
  7 -> 111
  ```

* **Resultado:** `000 001 111 111 111`$_2$ (o `1111111111`$_2$)

**95)** `03700`

* **Desarrollo:**

  ```
  0 -> 000
  3 -> 011
  7 -> 111
  0 -> 000
  0 -> 000
  ```

* **Resultado:** `000 011 111 000 000`$_2$ (o `111111000000`$_2$)

**96)** `05255`

* **Desarrollo:**

  ```
  0 -> 000
  5 -> 101
  2 -> 010
  5 -> 101
  5 -> 101
  ```

* **Resultado:** `000 101 010 101 101`$_2$ (o `101010101101`$_2$)

## Convierte de hexadecimal a binario

**97)** `DA`

* **Desarrollo:**

  ```
  D -> 1101
  A -> 1010
  ```

* **Resultado:** `1101 1010`$_2$

**98)** `7C`

* **Desarrollo:**

  ```
  7 -> 0111
  C -> 1100
  ```

* **Resultado:** `0111 1100`$_2$

**99)** `B5`

* **Desarrollo:**

  ```
  B -> 1011
  5 -> 0101
  ```

* **Resultado:** `1011 0101`$_2$

**100)** `F0A5`

* **Desarrollo:**

  ```
  F -> 1111
  0 -> 0000
  A -> 1010
  5 -> 0101
  ```

* **Resultado:** `1111 0000 1010 0101`$_2$

**101)** `0F0F`

* **Desarrollo:**

  ```
  0 -> 0000
  F -> 1111
  0 -> 0000
  F -> 1111
  ```

* **Resultado:** `0000 1111 0000 1111`$_2$ (o `1111 0000 1111`$_2$)

**102)** `8001`

* **Desarrollo:**

  ```
  8 -> 1000
  0 -> 0000
  0 -> 0000
  1 -> 0001
  ```

* **Resultado:** `1000 0000 0000 0001`$_2$

## Nombra los polinomios por su exponente más alto y número de términos

**103)** $5n + 5$

* **Nombre:** Binomio lineal

* **Grado:** 1 (lineal)

* **Términos:** 2 (binomio)

**104)** $-10p^3 - 6 + 9p^2 - 4p^5 - 2p^8$

* **Nombre:** Polinomio de octavo grado con cinco términos

* **Grado:** 8

* **Términos:** Polinomio de octavo grado con cinco términos

**105)** $7x^8$

* **Nombre:** Monomio de octavo grado

* **Grado:** 8

* **Términos:** 1 (monomio)

**106)** $-2n + n^4 + 10n^6$

* **Nombre:** Trinomio de sexto grado

* **Grado:** 6

* **Términos:** 3 (trinomio)

**107)** $5$

* **Nombre:** Monomio constante

* **Grado:** 0 (constante)

* **Términos:** Monomio constante

**108)** $5v^7$

* **Nombre:** Monomio del séptimo grado

* **Grado:** 7 (séptimo)

* **Términos:** Monomio

## Resuelve las siguientes preguntas

**109)** Amy puede verter una gran entrada de concreto en ocho horas. Un día su amiga Jill la ayudó y solo tomó 3,08 horas. Encuentra cuánto le tomaría a Jill hacerlo sola.

* **Planteamiento:**

  * Tabla de datos:

    * **Amy:** $C(1) = x$, $8\text{ hrs}$

    * **Amy y Jill:** $C(2) = x \text{ y } J$, $3.08\text{ hrs}$

    * **Jill:** $C(1) = x$, $?\text{ hrs}$

  * Ecuación: $\text{Trabajo de Amy} + \text{Trabajo de Jill} = \text{Trabajo total}$

    $$
    \frac{1}{8}(3.08) + \frac{1}{T}(3.08) = 1
    $$

* **Desarrollo:**

  $$
  \frac{3.08}{8} + \frac{3.08}{T} = 1
  $$

  $$
  \frac{1}{8} = 0.125 = 12.5\%
  $$

  $$
  3.08 \times 0.125 = 38.5\%
  $$

  $$
  0.385 + \frac{3.08}{T} = 1
  $$

  $$
  \frac{3.08}{T} = 1 - 0.385
  $$

  $$
  \frac{3.08}{T} = 0.615
  $$

  $$
  1 - 0.385 = 61.5\%
  $$

  $$
  T = \frac{3.08}{0.615}
  $$

* **Resultado:**

  $$
  T = 5.008\text{ horas}
  $$

**110)** Jaidee puede cavar un hoyo de 10 pies por 10 pies en cinco horas. Ted puede cavar el mismo hoyo en siete horas. Si trabajaran juntos, ¿cuánto tiempo les tomaría?

* **Planteamiento:**

  * **Datos:**

    * $10 \times 10\text{ pies} = 30.48\text{ metros}$ (1 hueco)

    * **Jaidee:** $5\text{ horas}$, $30.48\text{ metros}$

    * **Ted:** $7\text{ horas}$, $30.48\text{ metros}$

  * Ecuación: $\text{Jaidee} + \text{Ted} = \text{Tiempo total}$

* **Desarrollo:**

  * Tasas individuales:

    * $\text{Jaidee} = \frac{1}{5}$

    * $\text{Ted} = \frac{1}{7}$

  * Suma de fracciones:

    $$
    \frac{1}{5} + \frac{1}{7} = \frac{7 + 5}{35} = \frac{12}{35}
    $$

  * Inversión para hallar el tiempo:

    $$
    \frac{12}{35} \longrightarrow \frac{35}{12} = 2.916\text{ horas}
    $$

* **Resultado:**

  $$
  2.916\text{ horas}
  $$

**111)** Un avión de carga salió de Los Ángeles y voló hacia Moscú. Un avión de la Fuerza Aérea salió cuatro horas después volando a 310 km/h en un esfuerzo por alcanzar al avión de carga. Después de volar durante seis horas, el avión de la Fuerza Aérea finalmente lo alcanzó. ¿Cuál era la velocidad promedio del avión de carga?

* **Planteamiento y Fórmulas:**

  * $v = \frac{d}{t} \implies d = v \cdot t$

  * **Avión Fuerza Aérea:**

    * Velocidad = $310\text{ km/h}$

    * Tiempo = $6\text{ horas}$

  * **Avión de Carga:**

    * Tiempo total de vuelo = $6\text{ horas} + 4\text{ horas} = 10\text{ horas}$

* **Desarrollo:**

  * Calculamos la distancia recorrida por el avión de la Fuerza Aérea:

    $$
    \text{Distancia} = 310\text{ km/h} \cdot 6 = 1860\text{ km}
    $$

  * Calculamos la velocidad promedio del avión de carga:

    $$
    \text{Velocidad promedio} = \frac{1860}{10} = 186\text{ km/h}
    $$

* **Resultado:**

  $$
  \text{Velocidad promedio} = 186\text{ km/h}
  $$

**112)** Un tren de carga viajó a Nueva York y de regreso. En el viaje de ida viajó a 35 km/h y en el viaje de regreso fue a 49 km/h. ¿Cuánto tiempo tomó el viaje de ida si el viaje de regreso tomó diez horas?

* **Planteamiento:**

  * $t = \frac{d}{v}$

  * **Viaje de regreso:**

    * Velocidad ($v_r$) = $49\text{ km/h}$

    * Tiempo ($t_r$) = $10\text{ horas}$

  * **Viaje de ida:**

    * Velocidad ($v_i$) = $35\text{ km/h}$

* **Desarrollo:**

  * Calculamos la distancia del viaje de regreso:

    $$
    d_r = 49\text{ km/h} \cdot 10 = 490\text{ km}
    $$

  * Calculamos el tiempo del viaje de ida:

    $$
    t = \frac{490\text{ km}}{35\text{ km/h}} = 14\text{ horas}
    $$

* **Resultado:**

  $$
  t = 14\text{ horas}
  $$

**113)** 1 yd³ de tierra que contenía 30% de arena se mezcló con 4 yd³ de tierra que contenía 20% de arena. ¿Cuál es el contenido de arena de la mezcla?

* **Planteamiento y Desarrollo:**

  * Volumen total de tierra = $1 + 4 = 5\text{ yd}^3$

  * Cálculo de arena por componente:

    * Componente 1: $1 \cdot 0.30 = 0.30\text{ yd}^3$

    * Componente 2: $4 \cdot 0.20 = 0.80\text{ yd}^3$

  * Suma total de arena:

    $$
    0.30\text{ yd}^3 + 0.80\text{ yd}^3 = 1.10\text{ yd}^3
    $$

  * Porcentaje de arena en la mezcla total:

    $$
    \text{Porcentaje} = \frac{1.10}{5} = 0.22 \times 100 = 22\%
    $$

* **Resultado:**

  $$
  22\%\text{ de arena}
  $$

**114)** Para su fiesta de cumpleaños, James mezcló 7 L de ponche de frutas de la Marca A y 6 L de la Marca B. La Marca A contiene 11% de jugo de fruta y la Marca B contiene 24% de jugo de fruta. ¿Qué porcentaje de la mezcla es jugo de fruta?

* **Planteamiento:**

  * Marca A y B: $7\text{ L} + 6\text{ L} = 13\text{ L}$ (volumen total)

  * Contenido de jugo de fruta:

    * Marca A ($11\%$): $7 \cdot 0.11 = 0.77\text{ L}$

    * Marca B ($24\%$): $6 \cdot 0.24 = 1.44\text{ L}$

* **Desarrollo:**

  * Suma de jugo puro de fruta:

    $$
    0.77\text{ L} + 1.44\text{ L} = 2.21\text{ L}
    $$

  * Cálculo del porcentaje sobre la mezcla total ($13\text{ L}$):

    $$
    \text{Porcentaje} = \frac{2.21}{13} = 0.17
    $$

    $$
    0.17 \times 100 = 17\%
    $$

* **Resultado:**

  $$
  17\%\text{ de jugo de fruta}
  $$