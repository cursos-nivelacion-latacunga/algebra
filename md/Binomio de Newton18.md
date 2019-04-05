# Expresiones Algebraicas

**Tema de la clase** Signo sumatorio. Inducción matemática. Números factoriales. Binomio de Newton.

**Objetivo de la clase**  Definir signo sumatorio, inducción matemática, los números factoriales y  binomio de Newton. 

## Binomio de Newton 

## Notación Factorial 

La notación $n!$ se lee "$n factorial$", y se define como el produco indicado de todos los numeros consecutivamente desde $n$ hasta $1$:

$n!=n*(n-1)*(n-2)*(n-3)...1$ para cualquier entero positivo $n$

### Ejemplos 

$2!=2*1=2$

$3!=3*2*1=6$

$4!=4*3*2*1=24$

$5!=5*4*3*2*1=120$

$6!=6*5*4*3*2*1=720$

Por definición.

$0!=1$

## Coeficientes Binomiales

Para $n$ y $r$ eteros no negativos, $n>r$ 

${n}\choose{r}$ $=C(n,r)=\dfrac{n!}{(n-r)! r!}$ 

### Ejemplos

- Evaluar: 

    ${5}\choose{2}$ $=C(5,2)=\dfrac{5!}{(5-2)! 2!}= \dfrac{5!}{3!* 2}= \dfrac{5*4*3!}{3!* 2}$ Simplificamos $\dfrac{5*4}{2}=10$

    ${7}\choose{4}$ $=C(7,4)=\dfrac{7!}{(7-4)! 4!}= \dfrac{7!}{3! * 4!}= \dfrac{7*6*5*4!}{6* 4!}$ Simplificamos $\dfrac{7*6*5}{6}=35$

    ${4}\choose{4}$ $=C(4,4)=\dfrac{4!}{(4-4)! 4!}= \dfrac{4!}{0! * 4!}$ Simplificamos $\dfrac{1}{1}=1$

    ${3}\choose{0}$ $=C(3,0)=\dfrac{3!}{(3-0)! 0!}= \dfrac{3!}{3! * 0!}$ Simplificamos $\dfrac{1}{1}=1$

Entonces se puede observar que para cualquier entero positivo n:

- ${n}\choose{n}$ $=C(n,n)=1$

- ${n}\choose{0}$ $=C(n,0)=1$

- ${n}\choose{r}$ $=$ ${n}\choose{n-r}$

## Teorema del Binomio
Para cualquier entero positivo n:
 
$(a + b)^n=$ ${n}\choose{0}$ $a^n b^0$ + ${n}\choose{1}$ $a^{n-1}  b^{1}$ + ${n}\choose{2}$ $a^{n-2}  b^{2}$ + ${n}\choose{3}$ $a^{n-3}  b^{3}$ + ${n}\choose{4}$ $a^{n-4}  b^{4}$+ .... + ${n}\choose{n-1}$ $ab^{n-1}$ + ${n}\choose{n}$ $a^{0}  b^{n}$


Como se observa en el teorema del Binomio "la suma de los exponentes de las variables en cada termino es $n$ y que el numero inferior de la combinación siempre es igual al del exponente de la segunda varibale del termino".

Si se tiene $(a + b)^n$, todos los terminos son positivos y si se tiene la forma $(a - b)^n=$, los terminos impares positivos y los terminos pares son negativos.


### Ejemplos

- $(2x + 3)^6=$ ${6}\choose{0}$ $(2x)^6 (3)^0$ + ${6}\choose{1}$ $(2x)^{5} (3)^{1}$ + ${6}\choose{2}$ $(2x)^{4}  (3)^{2}$ + ${6}\choose{3}$ $(2x)^{3}  (3)^{3}$ + ${6}\choose{4}$ $(2x)^{2}  (3)^{4}$+ ${6}\choose{5}$ $(2x)^{1} (3)^{5}$ + ${6}\choose{6}$ $(2x)^{0}  (3)^{6}$


    $= (1)$ $(2x)^6 (1)$ + $(6)$ $(2x)^{5} (3)$ + $(15)$ $(2x)^{4} (9)$ + $(20)$ $(2x)^{3}  (27)$ + $(15)$ $(2x)^{2}  (81)$+ $(6)$ $(2x)^{1} (243)$ + $(1)$ $(2x)^{0}  (729)$

    $=  64x^6$ + $(18)$ $(32x^{5})$ + $(135)$ $(16x^{4})$ + $(540) (8x^{3})$ + $(1215)$ $(4x^{2})$+ $(1458)$ $(2x)$ + $729$

    $= 64x^6$ + $576 x^{5}$ + $2160 x^{4}$ + $4320 x^{3}$ + $4860 x^{2}$+ $2916x$ + $729$

- $\left(\dfrac {1}{x} - 2 \sqrt{x} \right)^5=$ ${5}\choose{0}$ $\left(\dfrac {1}{x} \right)^5 (2 \sqrt{x})^0$ + ${5}\choose{1}$ $\left(\dfrac {1}{x} \right)^{4} (2 \sqrt{x})^{1}$ + ${5}\choose{2}$ $\left(\dfrac {1}{x} \right)^{3}  (2 \sqrt{x})^{2}$ + ${5}\choose{3}$ $\left(\dfrac {1}{x} \right)^{2}  (2 \sqrt{x})^{3}$ + ${5}\choose{4}$ $\left(\dfrac {1}{x} \right)^{1}  (2 \sqrt{x})^{4}$+ ${5}\choose{5}$ $\left(\dfrac {1}{x} \right)^{0}  (2 \sqrt{x})^{5}$

    $=$ $(1)$ $\left(\dfrac {1}{x^5} \right) (1)$ - $(5)$ $\left(\dfrac {1}{x^{4}} \right) (2 {x}^\frac{1}{2})$ + $(10)$ $\left(\dfrac {1}{x^{3}} \right) (4x)$ - $(10)$ $\left(\dfrac {1}{x^{2}} \right)  (8  {x}^{\frac{3}{2}})$ + $(5)$ $\left(\dfrac {1}{x} \right)  (16 x^{2})$ - $(1)$ $(1) (32 {x}^\frac{5}{2})$

    $= \dfrac {1}{x^5}$ - $\dfrac{10}{x^{\frac{7}{2}}}$ + $\dfrac {40}{x^{2}}$ - $\dfrac{80} {{x}^{\frac{1}{2}}}$ + $80x$ - $32 {x}^\frac{5}{2}$

## Termino General $T_r$

$T_r=$ Lugar que ocupa el termino buscado. 

$T_r=$ ${n}\choose{r}$ $a^{n-r} b^{r}$

$a=$ Primer termno del binomio.

$b=$ Segundo termino del binomio

$r=$ Lugar menos uno del termino buscado

$n=$ Exponente del binomio.


### Ejemplos 

- Calcular el termino medio de $\left(\sqrt{x}+\dfrac{1}{\sqrt {x}} \right)^{4}$

    El termino medio es el tercer termino por lo tanto: 

    $a= \sqrt{x}$

    $b= \dfrac{1}{\sqrt {x}}$

    $r=3-1=2$

    $n=4$

    Reemplazamos valores y realizamos las operaciones.

    $T_r=$ ${n}\choose{r}$ $a^{n-r} b^{r}$


    $T_3=$ ${4}\choose{2}$ $(\sqrt{x})^{3-1}\left(\dfrac{1}{\sqrt {x}} \right)^{2}$


    $= (6)$ $(\sqrt x)^2 \left(\dfrac{1}{x} \right)$


    $= (6)$ $(x) \left(\dfrac{1}{x}\right)$

    $= 6$

- Calcular el octavo termino de  $(x^{\frac{1}{2}}+ y^{\frac{1}{2}})^{12}$

    $a= x^{\frac{1}{2}}$

    $b= y^{\frac{1}{2}}$

    $r=8-1=7$

    $n=12$

    Reemplazamos valores y realizamos las operaciones.

    $T_r=$ ${n}\choose{r}$ $a^{n-r} b^{r}$


    $T_7=$ ${12}\choose{7}$ $(x^{\frac{1}{2}})^{12-7} (y^{\frac{1}{2}})^{7}$


    $= (792)$ $(x^{\frac{1}{2}})^{5} (y^{\frac{1}{2}})^{7}$

    $= 792$ $x^{\frac{5}{2}} y^{\frac{7}{2}}$


## Bibliografía

- SILVA,José. 2011. ***Algebra***.

- García García, Juan Ignacio; García Sánchez, Pedro A; Urbano Blanco, Juan Manuel, [Fundamentos lógicos de la programación](http://hdl.handle.net/10481/43278), Universidad de Granada.

## Tarea en casa

Pagina 29. Ejercicio de Refuerzo  del  1 al 8.







































