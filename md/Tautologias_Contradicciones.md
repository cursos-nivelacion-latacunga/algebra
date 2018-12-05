 Lógica proposicional


**Tema de la clase** Tautologías y contradicciones. Relaciones entre proposiciones: implicación y equivalencia lógica. 

**Objetivo de la clase** Evaluar formulas lógicas según las tablas de verdad de cada conectivo lógico e identificar cuando es una tautología y una contradicción, además determinar si es una implicación o equivalencia lógica.  

# Tautologia

Son proposiciones compuestas que siempre son verdaderas cualquiera que sea el valor de las proposiciones componentes.

# Contradicción
Son proposiciones compuestas que siempre son falas cualquiera que sea el valor de las proposiciones componentes.

# Contingencia 
Son proposiciones compuestas que no son ni tautológia ni contradiciones, es decir, son proposiciones que en algunos casos es **F**, y en otros es **V**.

# Implicación lógica
Es implicación lógica cuando  exista una proposicion condicional $→$ y la tabla de verdad sea una tautología.

# Equivalencia lógica
Es equivalencia lógica cuando  exista una proposicion bicondicional $↔$ y la tabla de verdad sea una tautología.

## Fórmula Logica

Fórmula sintactica donde se pueden combinar cualquier número finito de proposiciones cuyos valores de verdad pueden ser conocidos, construyendo su tabla de verdad, en dicha tabla se puede indicar los valores resultantes de estas proposiciones compuestas, para todas las combinaciones posibles de valores de verdad de las proposiciones compuestas.

Para calcular el valor de verdad de las proposiciones dadas, utilizar:

$2^n$

donde $n=$ número de proposiciones de la fórmula lógica.

### Ejemplo
- $[(p → q)$ v $p ]$ $⌐q$ 

    $2^2=4$ valores de verdad de la tabla.

- $(q$ v $p)$ $˄$ $⌐r$

    $2^3=8$ valores de verdad de la tabla.


- $(p$ $˄$ $r)$→($s$ v $q)$

    $2^4=16$ valores de verdad de la tabla.
    

## Jerarquía de los conectivos Lógicos.

Para realizar las operaciones primero se debe empezar a resolver  las proposiciones que esten dentro de los parentesis, luego todas las negaciones y se avanza de izquierda a derecha, los corchetes son considerados como paréntesis.

### Ejemplo 
Hallar la tabla de verdad de las siguientes fórmulas lógicas e indicar si es una tautología, contradición o contingencia.

- $[(⌐p$ v $q)$ $˄$ $⌐q)]$ $→$ $⌐p$


|$p$|$q$|$[(⌐p$|v|$q)$|$˄$ |$⌐q)]$ |$→$|$⌐p$|
|:--|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---:|
|  V|V|  F|**V**|V|**F**| F |**V**|F|
|  V|F|  F|**F**|F|**F**| V |**V**|F|
|  V|V|  V|**V**|V|**F**| F |**V**|V|
|  V|F|  V|**V**|F|**V**| V |**V**|V|
 
    Es una Tautología y por lo tanto una Implicación lógica.

- $[p$ $˄$ $(p$ v $q)]$ $↔$ $p$


|$p$|$q$|$[p$|$˄$|$(p$| v |$q ) ]$ |$↔$|$p$|
|:--|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---:|
|  V|V|  V|**V**|V|**V**| V |**V**|V|
|  V|F|  V|**V**|V|**V**| F |**V**|V|
|  V|V|  F|**F**|F|**V**| V |**V**|F|
|  V|F|  F|**F**|F|**F**| F |**V**|F|
 
    Es una Tautología y por lo tanto una Equivalencia lógica.

- $[p$ v $(q$ $→$ $⌐r)]$ 


|$p$|$q$|$r$|$[p$|v|$(q$| $→$ |$⌐r)]$|
|:---|:---:|:---:|:---:|:---:|:---:|:---:|----:|
|  V|V|  V|V|**V**|V| **F** |F|
|  V|V|  F|V|**V**|V| **V** |V|
|  V|F|  V|V|**V**|F| **V** |F|
|  V|F|  F|V|**V**|F| **V** |V|
|  F|V|  V|F|**F**|V| **F**|F|
|  F|V|  F|F|**V**|V| **V** |V|
|  F|F|  V|F|**V**|F| **V** |F|
|  F|F|  F|F|**V**|F| **V** |V|
 
     Es una Contingencia.

- $(q$ v $p)$ $˄$ $⌐p$

|$p$|$q$|$(q$|v|$p)$| $˄$|$⌐p$|
|:--|:---:|:---:|:---:|:---:|:---:|---:|
|  V|V|  V|**V**|V|**F**| F |
|  V|F|  F|**V**|V|**F**| F |
|  F|V|  V|**V**|F|**V**| V |
|  F|F|  F|**F**|F|**F**| V |

    Es una Contingencia.



# Bibliografía

- ESPINOZA,Eduardo. 2005. ***Matemática Básica***. Perú:Lima.

- García García, Juan Ignacio; García Sánchez, Pedro A.; Urbano Blanco, Juan Manuel, [Fundamentos lógicos de la programación](http://hdl.handle.net/10481/43278), Universidad de Granada.

# Tarea en casa

Página 50,51,52. Ejercicios 8,14 y 22 del Libro Matemática Básica.

