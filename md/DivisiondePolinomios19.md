# Expresiones Algebraicas

**Tema de la clase** División de Polinomios: Métodos: Clásico, Algoritmo de la División (Coeficientes indeterminados), Regla de Ruffini, Teorema del Resto y del Factor. 

**Objetivo de la clase**  Resolver ejercicios de División de polinomios, mediante el método Clásico, Algoritmo de la División , Regla de Ruffini, Teorema del Resto y del Factor. 

## Divsión de Polinomios 

## Metodo Clásico o de la Galera. 

- $(6x^{12} - 4x^8 +1) ÷ ( 3x^4  -1)$

- $(3x^{5n-3} - 23 x^{5n-2} + 5 x^{5n-1} + 46 x^{5n} - 30 x^{5n+1}) ÷ (x^{3n-3} + 6 x^{3n-1} - 8 x^{3n-2})$


## Metodo de Ruffini

Este metodo tambien conocido como division sintetica se emplea para hallar el cociente y el residuo sin efectuar la divisón. es valido solamente cuando se divide un polinomio ordenado $P(x)$ para un binomio de primer grado de la forma $ax ± b$ o cualquier otra expresión transformable a esta

1. Caso I $P(x) ÷ (x ± b)$

    Cuando el primer coeficiente del divisor es la unidad.

    $\left(2x^4 + 3x^2 -3x + \dfrac{22}{81}\right) ÷ \left(x -\dfrac{22}{81}\right)$

2. Caso II $P(x) ÷ (ax ± b)$

    Cuando el coeficiente del divisor es diferente de la unidad $(ax ± b); a≠1$. En este caso se procede en forma similar al caso I pero se debe tener presente que el cociente resultante es un cociente falso $Q_1(x)$; para obtener el cociente verdadero $Q(x)$ se divide cada uno de los coeficientes del cociente falso entre el primer coeficiente del divisor, es decir $Q(x)=Q_1(x) ÷ a$.

    $(-4x^4 + 3x^3- 6x^2 + x - 4) ÷ (-2x -1)$

3. Cao III: Cambio de variable

    Si el divisor es de grado mayor que uno.

    $(6x^{12} - 4x^8 +1) ÷ ( 3x^4  -1)$

## Metodo de los coeficientes interminados.

Este metodo sirve para encontrar el cociente y el residuo sin efectuar la dicisón entre dos polinomios $P(x)$ y $Q(x)$ de cualquier grado y se basa en el algoritmo de la division.

**Algoritmo de la divisón**

$P(x)=D(x).Q(x)+R(x)$

Para su aplicacion se debe considerar lo siguiente:
1. El grado del polinomio debe ser mayor o igual al grado del divisor; $G.P(x)≥ G.D(x)$
2. El grado del cociente es igual a la diferencia de los grados de los polinomios anteriores; $G.Q(x)=G.P(x)-G.Q(x)$

3. El grado del residuo es al menos un grado menor que el grado del divisor.

4. Se plantea el algoritmo de la divisón

5. Se desarrolla el segundo miembro de la igualdad.

6.  Se igualan los coeficientes de ls terminos de igual grado.

7. Se resuelve el sistema de ecuaiones obtenido.

Tanto el cociente como el residuo se expresaran como polinomios de coeficientes indeterminados.

|Grado del polinomio|Polinomio de coeficientes determinados|Polinomio de coeficientes indeterminados|
|:--:|:---:|:--:|
|  $0$|$8$|  $A$|
|  $1$|$-3x+2$|  $Ax+B$|
|  $2$|$4x^2-3x+4$| $Ax^2+Bx+C$|
|  $3$|$x^3-5x$|  $Ax^3+Bx^2+Cx+D$|
|  ...|...|  ...|

### Ejemplo

- Hallar el cociente y el residuo de la division $(2x^3 - 5x^2 + 7 x + 4) ÷ (x-3)$


    Determinaremos los grados de los polinomios.

    $P(x)=(2x^3 - 5x^2 + 7 x + 4)$  

    $G.P(x)=3$ ; Grado 3

    $D(x)=(x-3)$ 
    $G.D(x)=1$ ; Grado 1

    $G.Q(x)=G.P(x)- G.D(x)$
    
    $G.Q(x)=3-1=2$ ; Grado 2

    Entonces 

    $Q(x)=Ax^2+Bx+C$ 

    $G.R(x)= G.D(x)-1$

    $G.R(x)=1-1=0$ ; Grado 0

    $R(x)=D$


    Aplicando el algoritmo de Division 

    $P(x)=D(x).Q(x)+R(x)$

    $2x^3 - 5x^2 + 7 x + 4= (x-3) (Ax^2+Bx+C) + D$

    Realizamos la multiplicacion.

    $2x^3 - 5x^2 + 7 x + 4= Ax^3 + B x^2+Cx -3Ax^2 - 3Bx -3C + D$

    Agrupamos terminos semejantes
    
    $2x^3 - 5x^2 + 7 x + 4= Ax^3 + (B-3A) x^2 + (C -3B)x -3C + D$

    Igualamos lo coeficientes de los terminos de igual grado, es decir:

    |  Termino|Coeficiente|  Polinomio de coeficientes interminados|Valores correspondientes|
    |:--:|:---:|:--:|:--:|
    |  $x^3$|$2$|  $A$| $A=2$|
    |  $x^2$|$-5$|  $B-3A$|  $B-3A=-5$ $B=-5+3A$ $B=-5+3(2)$ $B=-5+6$ $B=1$|
    |  $x$|$7$| $C -3B$| $C-3B=7$ $C=7+3B$ $C=7+3(1)$ $C=10$|
    |  $x^0$|$4$|  $-3C + D$| $-3C + D=4$ $D=4+3C$ $D=4+3(10)$ $D=34$ |

    Por lo tanto se reemplaza los valores obtenidos en $Q(x)$ y $D(x)$ 

    $Q(x)=Ax^2+Bx+C$ 

    $Q(x)=2x^2+x+10$ 

    $R(x)=34$

## Teorema del Resto 

Se emplea para hallar directamente el residuo de la divisón de un polinomio entero en "$x$" entre un binomio de la forma $ax ± b$.

El residuo de la division de un polinomio $P(x)$ entre un binomio de la forma $ax ± b$, es igual al valor numerico que toma el polinomio cuando se reemplza $x$ por $\left(-\dfrac{b}{a}\right)$, que resulta de igualar a cero el divisor.

$ax ± b=0$, $x=\left(-\dfrac{b}{a}\right)$. 

Es decir el Residuo$=R(x)=P\left(-\dfrac{b}{a}\right)$ al Polinomio evaluado en $\left(-\dfrac{b}{a}\right)$.

### Ejemplo

- Hallar el residuo de la siguiente división $(2x^3 - 5x^2 + 7 x + 4) ÷ (x-3)$

    $P(x)=(2x^3 - 5x^2 + 7 x + 4)$
    $D(x)=(x-3)$ ; $x-3=0$ $x=3$

    Residuo $=R(x)=P(3)=2(3)^3 - 5(3)^2 + 7 (3) + 4$

    $R(x)=2(27)-5(9)+21+4$

    $R(x)=54-45+21+4$

    $R(x)=34$

- Hallar el residuo en la divisón:

    $\left(\dfrac{6x^{40} - 31x^{30} + 47 x ^{20} -56 x^{10}  +57}{2x^{10}-7}\right)$

    Realizaremos un cambio de variable para suprimir varios pasos.

    $x^{10}=y$

    Reemplazamos  y la division sera:

    $\left(\dfrac{6y^4 - 31y^3 + 47 y ^2 -56 y  +57}{2y-7}\right)$

    Entonces: 

    $P(y)=(6y^4 - 31y^3 + 47 y ^2 -56 y  +57)$

    $D(y)=(2y-7)$ ; $2y-7=0$ $y=\dfrac{7}{2}$

    Residuo $=R(y)=P\left(\dfrac{7}{2} \right)= 6 \left(\dfrac{7}{2} \right)^4 - 31\left(\dfrac{7}{2} \right)^3 +47 \left(\dfrac{7}{2} \right)^2- 56 \left(\dfrac{7}{2} \right) + 57$

    $R(y)=\left(\dfrac{7203}{8} \right) - \left(\dfrac{10633}{8} \right) + \left(\dfrac{2303}{4} \right) -196+57$

    $R(y)=8=R(x)$


## Teorema del Factor

Si el valor numerico que toma el polinomio es cero(0), se considera que el divisor es un Factor del Polinomio, es decir:
$P\left(-\dfrac{b}{a}\right)=0$; entonces, residuo igual a cero, por lo tanto se puede concluir que el divisor es un factor del polinomio y planteado el algoritmo de la división se tendria: $P(x)=(ax ± b)Q(x)$, esto quiere decir que la divison es exacta, el residuo $R(x)=0$.


### Ejemplo

- Determine el valor de $k$ para que $x+2$ sea un factor de $x^3-2x^2-10x+k$.

    Para que $x+2$ sea factor del polinomio debe cumplir que $P(-2)=0$

    Entonces sustituimos e igualamos a cero.

    $P(-2)=(-2)^3-2(-2)^2-10(-2)+k$

    $(-2)^3-2(-2)^2-10(-2)+k=0$

    $-8-2(4)+20+k=0$

    despejamos k

    $k=-20+8+8$

    $k=-4$

## Bibliografía

- SILVA,José. 2011. ***Algebra***.

- [Polinomios](https://cursos-0-fc-ugr.github.io/Matematicas/00-polinomios.html), de los [Cursos Cero](https://cursos-0-fc-ugr.github.io/) de [Matematicas](https://cursos-0-fc-ugr.github.io/Matematicas/)  la Facultad de Ciencias de la Universidad de Granada.

## Tarea en casa

Pagina 36. Ejercicio de Refuerzo  del  1 al 3. Del libro de Silva.




