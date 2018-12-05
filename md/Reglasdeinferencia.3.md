#Lógica proposicional


**Tema de la clase**  Reglas de inferencia. Métodos de demostración. Ejercicios. 

**Objetivo de la clase** Utilizar los métodos de demostración para comprobar la validez de una inferencia lógica.

## Inferencia lógica o argumento lógico

Es el proceso de pasar de un conjunto de premisas a una conclusión, es decir, una inferencia lógica es el proceso de obtención de una proposición a partir de otras proposiciones dadas, a las cuales se aplican reglas de inferencia, de tal manera que la conclusión sea consecuencia lógica de las premisas. 

la inferencia lógica es una condicional de la forma: 
- $(p1$ $˄$ $p2$ $˄$ $p3$ $˄$...$˄$ $p$n$)$ $→$ $q$

donde las proposiciones $p1$,$p2$...$p$n son llamadas premisas y que originan como consecuencia otra proposción $q$ llamada conclusión.

- Si la condicional es una tautología se denomina argumento válido o inferencia válida.

- Si la condicional no es una tautología se denomina  **Falacia**

## Concepto regla de inferencia

Una regla de inferencia es un razonamiento verdadero que valida la verdad de una conclusión a partir de premisas verdaderas; es decir, si las premisas son verdaderas, la conclusión también tendrá que ser verdadera.

## Reglas de inferencia 

### Modus Ponendo Ponens –MPP
Esta regla establece que si la implicación de premisas y su antecedente son verdaderos,su consecuente es necesariamente verdadero. Simbólicamente:

- $(p$ $→$ $q)$ $˄$ $p$ $→$ $q$

### Modus Tollendo Tollens –MTT
Esta regla señala que si la implicación de premisas es verdadera y su consecuente es falso, entonces su antecedente es necesariamente falso. Simbólicamente:

- $(p$ $→$ $q)$ $˄$ $⌐q$ $→$ $⌐p$

### Modus Tollendo Ponens –MTP
Esta regla indica que si una disyunción de premisas es cierta y una de sus premisas es falsa, entonces la otra premisa es necesariamente verdadera. Simbólicamente:

- $(p$ v $q)$ $˄$ $⌐p$ $→$ $q$           

    ó

- $(p$ v $q)$ $˄$ $⌐q$ $→$ $p$

### Regla de simplificación –RS
Esta regla establece que de la conjunción de premisas se puede inferir una de ellas. Simbólicamente:

- $(p$ $˄$ $q)$ $→$ $p$

    ó

- $(p$ $˄$ $q)$ $→$ $q$

### Regla de adición –RA
De esta regla se puede determinar que de una premisa se puede deducir como conclusión la disyunción de la premisa con otra cualquiera. Simbólicamente:

- $p$ $→$ $(p$ v $q)$

    ó

- $q$ $→$ $(p$ v $q)$

### Regla de silogismo hipotético –RSH 
Esta regla indica que si se tienen dos condicionales tales que el antecedente del segundo es el consecuente del primero, entonces se puede inferir como conclusión un condicional formado por el antecedente del primero y el consecuente del segundo. Simbólicamente:

- $(p$ $→$ $q)$ $˄$ $(q$ $→$ $r)$ $→$ $(p$ $→$ $r)$


## Deducción  Proposicional

Con el manejo de las reglas de inferencia  se puede demostrar que los razonamientos son válidos o no.  

 Una deducción formal es una serie de proposiciones o pasos en la cual cada paso es una premisa o está deducida directamente de los pasos que la preceden por medio de una determinada regla.

La deducción puede hacerse teniendo un argumento en forma simbólica o en forma oracional. 

#### Ejemplo 1

-  Demostrar que el siguiente argumento lógico da como consecuencia: $t$ $˄$ $s$ 

1) $e$ $→$ $s$
2) $⌐t$ $→$ $⌐j$  
3)   $e$ $→$ $j$

    Demostración 

1) $e$ $→$ $s$
2) $⌐t$ $→$ $⌐j$  
3)   $e$ $→$ $j$
_______

En 3 aplico RS.

4) $e$ 

En 1 y 4 aplico MPP
  
5) $s$  

En 3 aplico RS.


6) $j$      

En 2 y 6 aplico MTT


7) $t$      

En 5 y 7 aplico RA


8) $t$ $˄$ $s$

**Argumento Válido.**

#### Ejemplo 2

- Si la ballena es un mamífero, entonces toma oxigeno del aire. Si toma su oxigeno del aire, entonces no necesita branquias. La ballena es un mamífero y vive en el océano. Por lo tanto no necesita branquias.

**Demostración**

•**Identificar cada una de las proposiciones simples**

$p:$ La ballena es un mamífero

$q:$ La ballena toma su oxigeno del aire

$r:$ La ballena necesita branquias

$s:$ La ballena habita en el océano

•**Simbolizar ahora el argumento**

1) $p$ $→$ $q$
2) $q$ $→$ $⌐r$  
3)   $p$ $˄$ $s$
_______
Consecuencia $⌐r$

**Procedimiento lógico para llegar a esta conclusión, es decir, la deducción proposicional**
1) $p$ $→$ $q$
2) $q$ $→$ $⌐r$  
3)   $p$ $˄$ $s$ 
_______
En 3 aplico RS

4)	$p$		

En 1 y 4 aplico MPP

5)	$q$	

En 2 y 5 aplico MPP

6) $⌐r$ 	 		
    Argumento válido.

# Bibliografía

- ESPINOZA,Eduardo. 2005. ***Matemática Básica***. Perú:Lima.

- García García, Juan Ignacio; García Sánchez, Pedro A.; Urbano Blanco, Juan Manuel, [Fundamentos lógicos de la programación](http://hdl.handle.net/10481/43278), Universidad de Granada.

# Tarea en casa

Página 63. Ejercicios  95,96 del Libro Matemática Básica.


