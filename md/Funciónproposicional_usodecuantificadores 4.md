# Lógica proposicional


**Tema de la clase**  Función proposicional: uso de cuantificadores. Negación con proposiciones con cuantificadores. 

**Objetivo de la clase** Conocer y utilizar los cuantificadores universal, existencial y su negación para representar proposiciones afirmativas y negativas. 

## Función Proposicional 

A todo enunciado de la forma $P(x)$ se denomina función proposicional la cual tiene la propiedad de convertirse en una proposición al ser sustituido variable $x$ por una constante "a" especifica, al conjunto de todos los valores convenidos para la variable $x$ se denomina dominio de la variable.

### Ejemplo

- $P(x)=x+1<9$, si $x$ pertenece al conjunto de los enteros, entonces $P(x)$ es una funcion proposicional cuyo dominio es los enteros.

    Si $x=-2$ $Є$ $Z$, $-2+1<9$  es **Verdadero**

    Si $x=10$ $Є$ $Z$, $10+1<9$  es **Falso**

Por lo tanto $P(x)$ es una función proposicional.

## Cuantificadores
Permite obtener proposiciones a partir de una función proposicional.

Entonces:

La proposición $P(x)$, tal que $x$ $Є$ $U$ es verdadero para todos los conjuntos $U$.

La proposición $P(x)$, tal que $x$ $Є$ $U$ es verdadero para al menos un elemento del conjunto $U$.

Es decir, existe un elemento $a$ $Є$ $U$ para lo cual la proposición es verdadera.


**Cuantificador Universal** 

Se simboliza $(⍱x)$ y se lee para "todo $x$".

**Cuantificador Existencial** 

Se simboliza $(∃x)$ y se lee "existe $x$ tal que", "existen un" o "para algún".

#### Ejemplo

Represente mediante cuantificadores las siguientes proposiciones.

- Todos los ecuatorianos son optimistas.

    Todos 
    
    $(⍱x)$

    ecuatorianos 
    
    $x$

   -  $(⍱x)$  $x$ son optimistas.


- Algún ecuatoriano es optimista.

    Algún 
    
    $(∃x)$

    ecuatoriano 
    
    $x$

    - $(∃x)$  $x$ son optimistas.


## Negación de Cuantificadores

Para negar un cuantificador universal se utiliza. 

 - $⌐$ $[(⍱x)$  $P(x)]=$ $(∃x)$  $(⌐P(x))$ 

 Para negar un cuantificador existencial se utiliza. 

 - $⌐$ $[(∃x)$  $P(x)]=$ $(⍱x)$  $(⌐P(x))$

 #### Ejemplo 

 - Para todo valor $x$ pertenece al conjunto {$1,2,3,4$}

    $((⍱x)$ $Є$ {$1,2,3,4$}$)$  $(x^2<0)$    **Falso** 

    Comprobación 

    $1^2<0$ **F**

    $2^2<0$ **F**

    $3^2<0$ **F**

    $4^2<0$ **F**

    **Negación** 

    $((∃x)$ $Є$ {$1,2,3,4$}$)$  $(x^2≥0)$  **Verdadero**

    Comprobación 

    $1^2≥0$ **V**

    $2^2≥0$ **V**

    $3^2≥0$ **V**

    $4^2≥0$ **V**


Nota; la negación de signos es la siguiente:

$=$ ; $≠$ 

$<$ ; $≥$

$>$ ; $≤$ 

y Viceversa.


- El cuadrado de todo número real es  positivo.

    $((⍱x)$ $Є$ $R)$  $(x^2>0)$  **Falso** 

    Comprobación 

    $1^2>0$ **V**

    $2^2>0$ **V**

    $3^2>0$ **V**

    $4^2>0$ **V**

    Pero cuando $x=0$ 

    $0^2>0$ **F**
    
    **Negación** 

    $((∃x)$ $Є$ $R)$  $(x^2≤0)$  **Verdadero**

    Comprobación
    
    $1^2≤0$ **V**

    $2^2≤0$ **V**

    $3^2≤0$ **V**

    $4^2≤0$ **V**

    $0^2≤0$ **V**


- $x^2=16$ para algún Número Natural.

    $((∃x)$ $Є$ $N)$  $(x^2=16)$  **Verdadero**

    Comprobación 

    $1^2=16$ **F**

    $2^2=16$ **F**

    $3^2=16$ **F**

    $4^2=16$ **V**

    **Negación** 

    $((⍱x)$ $Є$ $N)$  $(x^2≠16)$  **Falso**

    Comprobación

    $1^2≠16$ **V**

    $2^2≠16$ **V**

    $3^2≠16$ **V**

    $4^2≠16$ **F**


- $((⍱x)$ $Є$ $R)$ $/$ $(x^2=x)$  **Falso** 

    Comprobación

    $1^2=1$ **V**
    
    $2^2=2$ **F**

    $3^2=3$ **F**

    $4^2=4$ **F**

    **Negación** 

    $((∃x)$ $Є$ $R)$ $/$ $(x^2≠x)$  **Verdadero**

    Comprobación 

    $1^2≠1$ **F**

    $2^2≠2$ **V**

    $3^2≠3$ **V**

    $4^2≠4$ **V**


## Bibliografía

- ESPINOZA,Eduardo. 2005. ***Matemática Básica***. Perú:Lima.

## Tarea en casa

Página 62. Ejercicios 88,89 del Libro Matemática Básica.

