# Lógica proposicional

**Tema de la clase** Proposiciones: simples y compuestas. Introducción a los conectores lógicos: negación, conjunción,  disyunción, condicional, bicondicional. Tablas de verdad. Ejercicios.

**Objetivo de la clase** Definir y reconocer  proposiciones simples a las que se les puede asignar un valor de verdad para relacionarlas entre sí con conectivos lógicos como: negación , conjunción, disyunción, condicional y  bicondicional para formar proposiciones compuestas que tienen un valor de verdad que puede ser determinado.  

## Proposiciones lógicas

Enunciado (frase u oracion) que puede ser calificado como verdadero o falso, sin ambiguedades (no ambas a la vez). Y denotadas con letras minusculas ($p$,$r$,$s$,$t$,...etc).

Se clasifican en simples y compuestas.

### Proposiciones simples

Es una proposición que no contiene ningun conectivo lógico.

#### Ejemplo de proposiciones simples

- $p:$ 25 es un numero par  (***Falso***). 
- $q:$ Granada es una Cuidad de España (***Verdadero***).
- $r:$ Emmy Noether fue la segunda mujer matemática que ayudó a Albert Einstein a alumbrar sus teorias (***Verdadero***).
- $s:$ 1+3=7 (***Falso***).
- x<7  (***No es una proposición***).
- ¡Hola que tal! (***No es una proposción***).
- Que día es hoy? (***No es una proposión***).

### Proposiciones compuestas

Es una proposción simple que contiene al menos un conectivo lógico.

#### Conectivos Lógicos

|NOMBRE|EXPRESIÓN| SIMBOLO LÓGICO | 
| ----| :---: | :--------------:|
|Negación| $\neg$| **no**|
|Conjunción| $\wedge$ |      **y**|
|Disyunción| $\vee$ |**ó**|
|Condicional o Implicación| $\to$|**Si,......,entonces,......**|
|Bicondicional o Equivalencia| $\leftrightarrow$| **......si y solo si,......**|

#### Ejemplos de propoposiciones compuestas

Sea:

- $p:$ 5 es impar. 

- $q:$ 2 es par.

Formar las siguientes proposiciones compuestas:

- $\neg p:$

    5 **no** es impar.
- $\neg q$ 

    2 **no** es par.
- $p\vee q:$
    
     5 es impar **o** 2 es par.
- $\neg q \wedge p:$ 

    2 **no** es par **y** 5 es impar
- $p \to  \neg q:$ 

    **Si** 5 es impar **entonces**, 2 **no** es par.
- $q \leftrightarrow p:$ 

    2 es par, **si y solo si**, 5 es impar.

Para determinar el valor de verdad de una proposición compuesta se utiliza la tabla de verdad de cada conectivo lógico, detallado a continuación. 

                
#### Negación

Si la proposición es verdadera **V**, su negación es Falsa **F** y viceversa.
                
|$p$|$\neg p$|
|:----|:----:|
|V|F|
|F|V|

#### Conjunción

La proposicion $p\wedge q$ es verdadera unicamente en el caso de que ambas sean verdaderas, caso contrario falso.
                
|$p$|$q$|$p\wedge q$|
|:----|:----:|:---:|
|V|V|V|
|V|F|F|
|F|V|F|
|F|F|F|

#### Disyunción

La proposición $p\vee q$ es falsa unicamente en el caso de que ambas sean falsas, caso contrario verdadero.
                
|$p$|$q$|$p \vee q$|
|:----|:----:|:---:|
|V|V|V|
|V|F|V|
|F|V|V|
|F|F|F|

#### Condicional o implicación

La proposición $p \to  q$ es falsa unicamente en el caso de que  $p$ sea verdadera y $q$ sea falsa, caso contrario verdadero.
                
|$p$|$q$|$p \to  q$|
|:----|:----:|:---:|
|V|V|V|
|V|F|F|
|F|V|V|
|F|F|V|

#### Bicondicional o equivalencia

La proposición $p \leftrightarrow q$ es verdadera cuando $p$ y $q$ tienen los mismos valores de verdad, caso contrario falso.               

|$p$|$q$|$p \leftrightarrow q$|
|:----|:----:|:---:|
|V|V|V|
|V|F|F|
|F|V|F|
|F|F|V|

#### Ejemplos

Sea:

- $r:$  $6 + 4 \neq  10$  (**F**)

- $s:$  La capital de Ecuador es Quito (**V**)

Formar las siguientes proposiciones compuestas y hallar su valor de verdad, utilizando la tabla de verdad que corresponda:

- $\neg r$

    $6 + 4 = 10$  (**V**)
    
- $\neg s$ 

    La capital de Ecuador **no** es Quito (**F**)

- $r$ v $s$ 
    
     $6 + 4 \neq  10$ **ó** La capital de Ecuador es Quito.

     |$r$|$r\vee s$ |$s$|
     |:---|:---:|---:|
     |  F|**V**|V|

- $\neg s \wedge   r$ 

   La capital de Ecuador **no** es Quito  **y** $6 + 4 \neq   10$

|$\neg s$|$\neg s \wedge   r$ |$r$|
|:---|:---:|---:|
|  F|**F**|F|

- $r \to  \neg s$ 

    **Si** $6 + 4 \neq   10$ **entonces**, La capital de Ecuador **no** es Quito.

    |$r$|$r \to  \neg s$ |$\neg s$|
     |:---|:---:|---:|
     |  F|**V**|F|

- $s \leftrightarrow r$ 

   La capital de Ecuador es Quito, **si y solo si**, $6 + 4 \neq   10$

|$s$|$s \leftrightarrow r$  |$r$|
|:---|:---:|---:|
|  V|**F**|F|

## Bibliografía

- ESPINOZA,Eduardo. 2005. ***Matemática Básica***. Perú:Lima.

- García García, Juan Ignacio; García Sánchez, Pedro A.; Urbano Blanco, Juan Manuel, [Fundamentos lógicos de la programación](http://hdl.handle.net/10481/43278), Universidad de Granada.

## Tarea en casa

Página 36,37. Ejercicios 1 y 2 del Libro Matemática Básica.
