# Expresiones Algebraicas

**Tema de la clase** Descomposición Factorial de Polinomios.    

**Objetivo de la clase**   Definir y aplicar la descomposición factorial de polinomios por evaluación para resolver ejercicios algebraicos. 

## Factorizacion de Polinomios

**Metodos**

1. **Factor Comun:** 

    Es una expresion que esta contenida en cada uno de los terminos del polinomio, es decir, consiste en encontrar el elemento común a un conjunto de sumandos.

    ### Ejemplo

    - $4x^{2}z^{3}-6xz^{2}-6xyz^{4} + 8x^{3}z^{2}$

        Factor común de los numeros: $2$ 

        Factor comun de las letras: $xz^{2}$ (se escoje las letras que se repiten en todos los terminos y de estas la que tenga menor exponente).

        Factor común para este polinomio: $2xz^{2}$

        Procedimiento: cada termino del polinomio dividido para el Factor común:

        $4x^{2}z^{3}÷2xz^{2}=2xz$
        $-6xz^{2}÷2xz^{2}=-3$
        $-6xyz^{4}÷2xz^{2}=-3yz^{2}$
        $8x^{3}z^{2}÷2xz^{2}=4x$

        Resultado: Factor comun que multiplica a todos los terminos luego de dividirlos.

        $4x^{2}z^{3}-6xz^{2}-6xyz^{4} + 8x^{3}z^{2}=2xz^{2}(2xz-3-3yz^{2}+4z)$

    - $2x^{m+2}y^{n-3}-8x^{m+3}y^{n-1} + 4x^{m}y^{-n}$

        Factor común de los numeros: $2$ 

        Factor comun de las letras: $x^{m}y^{n}$ (en este caso se descompone cada termino para poder encontrar los elementos que se repiten).


        Factor común para este polinomio: $x^{m}y^{n}$

        Procedimiento: cada termino del polinomio dividido para el Factor común:

        $2x^{m+2}y^{n-3}÷2x^{m}y^{n}= x^{2}y^{-3}$
        $-8x^{m+3}y^{n-1} ÷2x^{m}y^{n}= -4x^{3}y^{-1}$
        $4x^{m}y^{-n}÷2x^{m}y^{n}= 2y^{-2n}$   

        Resultado: Factor comun que multiplica a todos los terminos luego de dividirlos.

        $2x^{m+2}y^{n-3}-8x^{m+3}y^{n-1} + 4x^{m}y^{-n}=2x^{m}y^{n}(x^{2}y^{-3}-4x^{3}y^{-1}+2y^{-2n})$


2. **Por Agrupacion:**

    Consiste en agrupar convenientemente los terminos de un polinomio, a fin de obtener, en cada grupo formado, un factor que sea comun a todos los terminos, luego se procede como en el metodo factor comun.

    ### Ejemplos

    - $(a+b)x+ax^2-ay+bx^2-by$

        Agrupamos los terminos 
        $(a+b)x+(ax^2+bx^2)+(-ay-by)$

        Factor comun por cada agrupacion:
    
        $(a+b)x+(a+b)x^2-(a+b)y$

        Factor comun por cada termino del polinomio: $(a+b)$

        Procedimiento: cada termino del polinomio dividido para el Factor común:

        $(a+b)x÷(a+b)= x$

        $(a+b)x^2÷(a+b)= x^2$

        $-(a+b)y÷(a+b)= -y$  

        Resultado: Factor comun que multiplica a todos los terminos luego de dividirlos.

        $(a+b)x+ax^2-ay+bx^2-by= (a+b)(x+x^2-y)$

    - $a^{n+2}-a^2b^n-a^{n+1}b+ab^{n+1}+3 a^nb^2-3b^{n+2}$

        Agrupamos los terminos 
        $(a^{n+2}-a^{n+1}b + 3 a^nb^2)+(-a^2b^n+ab^{n+1}-3b^{n+2})$

        Factor comun por cada agrupacion:
    
        $(a^2-ab+3b^2)a^n-(a^2-ab+3b^2)b^n$

        Factor comun por cada termino del polinomio: $(a^2-ab+3b^2)$

        Procedimiento: cada termino del polinomio dividido para el Factor común:

        $(a^2-ab+3b^2)a^n÷(a^2-ab+3b^2)= a^n$

        $-(a^2-ab+3b^2)b^n÷(a^2-ab+3b^2)= - b^n$ 

        Resultado: Factor comun que multiplica a todos los terminos luego de dividirlos.

        $a^{n+2}-a^2b^n-a^{n+1}b+ab^{n+1}+3 a^nb^2-3b^{n+2}=(a^2-ab+3b^2) (a^n-b^n)$.

3. **Por evaluación:**

    Solo para factores de primer grado y se fundamenta en el metodo de la division utilizando la regla de Ruffini.

    Se debe tomar en cuenta ademas las siguientes condiciones.

    a. Si la suma de los coeficientes es cero, necesariamente x-1 es el factor del polinomio.

    b. Un posible factor puede que lo sea otra vez.

    Para aplicar este metodo es necesario que el polinomio tenga un termino independiente.

    Se presentan dos posibilidades:

    1. **Cuando el primer coeficiente es la unidad:**

        Obtenemos los divisores del termino independiente, y con ello ls posibles factores lineales.

        ### Ejemplo

        - $x^3-3x+2$

            Divisores del termino independiente: ±1,2

            Se puede observar que la suma de los coeficientes es cero por lo tanto se conoce que $x-1$ es factor, es decir realizamos el metodo de ruffini con $x=1$.

            $x^3-3x+2=(x-1)(x-1)(x+2)$

            Resultado

            $x^3-3x+2=(x-1)^2(x+2)$

    2. **Cuando el primer coeficiente es diferente de la unidad:**

        En este caso los posibles factores se obtienen dividiendo los divisores del termino independiente para los divisores del coeficiente del primer termino.

        ### Ejemplo

        - $6x^3+23x^2+16x+3$

            Divisores del termino independiente: $±1,2$
            
            Divisroes del coeficiente del primer termino: $±1,2,3,6$

            Realizamos el metodo de ruffini provando con los siguientes divisores= $± \dfrac{1,3}{1,2,3,6}=±1,3,\dfrac{1}{2},\dfrac{1}{3}, \dfrac{3}{2},$

            $6x^3+23x^2+16x+3=6(x+3) \left(x+\dfrac{1}{2} \right)\left(x+\dfrac{1}{3}\right)$

            $6x^3+23x^2+16x+3=6(x+3) \left(\dfrac{2x+1}{2} \right)\left(\dfrac{3x+1}{3}\right)$

            Resultado

            $6x^3+23x^2+16x+3=(x+3)(2x+1)(3x+1)$


4. **Criterio de artificio de Cálculo:**

    Consiste en identificar expresiones iguales directa o indirectamente mediante ciertas transformaciones, para luego hacer un cambio de variable adecuado que permita transofrmar una expresion aparentemente complicada en otra expresion sencilla.

    Tambien se pueden combinar varios metodos para llegar a la solución.


    ### Ejemplo 

    - $(x^2+7x+5)^2+ 3x^2+21x+5$

        Agrupar terminos.

        $(x^2+7x+5)^2+ (3x^2+21x)+5$

        Factor comun en el segundo termino.

        $(x^2+7x+5)^2+ 3(x^2+7x)+5$

        Cambio de variable $y=(x^2+7x)$ tenemos:

        $(y+5)^2+ 3y+5$

        Resolvemos el Producto notable:

        $y^2+10y+25+3y+5$

        $y^2+13y+30$

        Aplicamos metodo de factorización:

        $y^2+13y+30=(y+10)(y+3)$

        Reemplazando el valor original de y:

        $(x^2+7x+10)(x^2+7x+3)$

        Aplicamos metodo de factorizacion en el primer parentesis ya que en el segundo no es posible porque tiene raices imaginarias.
        
        $(x+5)(x+2)(x^2+7x+3)$

        Resultado:

        $(x^2+7x+5)^2+ 3x^2+21x+5= (x+5)(x+2)(x^2+7x+3)$

    - $x^{5m}-9x^{3m} y^{4n}$

        Factor comun:

        $x^{3m}(x^{2m}-9y^{4n})$

        Producto notable en el parentesis:

        $x^{3m}(x^{m}+3y^{2n})(x^{m}33y^{2n})$

        Resultado:

        $x^{5m}-9x^{3m} y^{4n}=x^{3m}(x^{m}+3y^{2n})(x^{m} - 3y^{2n})$

Para comprobar cualquier resultado de cada ejercicio debe realizar la multipliacion de polinomios ya aprendida en clases y tendra que obtener el polinomio original.


## Bibliografía

- SILVA,José. 2011. ***Algebra***.

- [Polinomios](https://cursos-0-fc-ugr.github.io/Matematicas/00-polinomios.html), de los [Cursos Cero](https://cursos-0-fc-ugr.github.io/) de [Matematicas](https://cursos-0-fc-ugr.github.io/Matematicas/)  la Facultad de Ciencias de la Universidad de Granada.

## Tarea en casa

Pagina 46. Ejercicio de Refuerzo  de la  12 al 18. Libro de Silva.






























